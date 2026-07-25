# Insurance Claims Data Platform Architecture


## Business Overview

An insurance company receives data from multiple operational systems including policy, customer, claims, and payment systems.

The objective is to build a scalable data platform that processes insurance data and provides analytics-ready datasets.


## High-Level Architecture


Source Systems

- Policy Management System
- Customer Management System
- Claims Processing System
- Payment System


        |
        |

Data Ingestion Layer

- Azure Data Factory
- API/File ingestion


        |
        |

Azure Data Lake Storage Gen2


        |
        |

Bronze Layer

Raw insurance data stored without modification


        |
        |

Silver Layer

Cleaned and transformed data using PySpark


        |
        |

Gold Layer

Business-ready analytical tables


        |
        |

Analytics

- Power BI
- Reporting
- Business Insights
