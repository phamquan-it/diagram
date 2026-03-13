# diagram
graph TD
    A[File của bạn] --> B{Có phải binary?}
    
    B -->|Không| C[Upload thẳng lên DeepSeek]
    
    B -->|Có| D{Là ảnh chụp màn hình?}
    
    D -->|Có chữ| E[Upload ảnh - DeepSeek đọc text]
    D -->|Không chữ| F[Không upload được]
    
    D -->|File khác| G[Chuyển đổi/mô tả thay thế]
    
    G --> H[Hex dump]
    G --> I[Trích xuất metadata]
    G --> J[Mô tả bằng lời]
    
    style C fill:#90EE90
    style E fill:#90EE90
    style F fill:#FFB6C1
    style H,I,J fill:#FFD700
