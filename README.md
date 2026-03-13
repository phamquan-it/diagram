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
    
    style C fill:#90EE90,stroke:#333,stroke-width:2px
    style E fill:#90EE90,stroke:#333,stroke-width:2px
    style F fill:#FFB6C1,stroke:#333,stroke-width:2px
    style H fill:#FFD700,stroke:#333,stroke-width:2px
    style I fill:#FFD700,stroke:#333,stroke-width:2px
    style J fill:#FFD700,stroke:#333,stroke-width:2px
