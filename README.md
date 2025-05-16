<!DOCTYPE html><html lang=en> <head><meta charset=UTF-8><meta name=viewport content="width=device-width, initial-scale=1.0"><title></title><link href="https://fonts.googleapis.com/css2?family=Inter:wght@400;500;600&family=Cinzel:wght@500;600&family=Fira+Sans:wght@400;500&display=swap" rel=stylesheet><link rel=stylesheet href=https://cdnjs.cloudflare.com/ajax/libs/font-awesome/6.0.0/css/all.min.css><style>
        :root {
            --primary: #2d3748;
            --secondary: #4a5568;
            --accent: #4299e1;
            --background: #f7fafc;
            --card-bg: #ffffff;
        }
        
        body {
            font-family: 'Inter', sans-serif;
            background: var(--background);
            color: var(--primary);
            margin: 0;
            padding: 0;
            line-height: 1.6;
        }

        .hero {
            min-height: 100vh;
            display: flex;
            align-items: center;
            justify-content: center;
            position: relative;
            overflow: hidden;
            background: linear-gradient(135deg, #1a202c 0%, #2d3748 100%);
        }

        .hero-content {
            text-align: center;
            color: white;
            z-index: 1;
            padding: 2rem;
            max-width: 800px;
        }

        .hero h1 {
            font-family: 'Cinzel', serif;
            font-size: 3.5rem;
            margin-bottom: 1rem;
            animation: fadeInUp 1s ease;
        }

        .hero p {
            font-size: 1.25rem;
            opacity: 0.9;
            margin-bottom: 2rem;
            animation: fadeInUp 1s ease 0.2s;
            animation-fill-mode: both;
        }

        .scroll-indicator {
            position: absolute;
            bottom: 2rem;
            left: 50%;
            transform: translateX(-50%);
            animation: bounce 2s infinite;
        }

        .projects-grid {
            display: grid;
            grid-template-columns: repeat(auto-fit, minmax(300px, 1fr));
            gap: 2rem;
            padding: 4rem 2rem;
            max-width: 1200px;
            margin: 0 auto;
        }

        .project-card {
            background: var(--card-bg);
            border-radius: 1rem;
            padding: 2rem;
            box-shadow: 0 4px 6px rgba(0, 0, 0, 0.1);
            transition: transform 0.3s ease, box-shadow 0.3s ease;
            position: relative;
            overflow: hidden;
        }

        .project-card:hover {
            transform: translateY(-5px);
            box-shadow: 0 8px 12px rgba(0, 0, 0, 0.15);
        }

        .project-card h2 {
            font-family: 'Cinzel', serif;
            color: var(--primary);
            margin-bottom: 1rem;
            font-size: 1.5rem;
        }

        .project-card p {
            color: var(--secondary);
            margin-bottom: 1.5rem;
        }

        .project-link {
            display: inline-flex;
            align-items: center;
            gap: 0.5rem;
            color: var(--accent);
            text-decoration: none;
            font-weight: 500;
            transition: color 0.3s ease;
        }

        .project-link:hover {
            color: #2b6cb0;
        }

        .tech-stack {
            display: flex;
            flex-wrap: wrap;
            gap: 0.5rem;
            margin-top: 1rem;
        }

        .tech-badge {
            background: #edf2f7;
            padding: 0.25rem 0.75rem;
            border-radius: 9999px;
            font-size: 0.875rem;
            color: var(--secondary);
        }

        @keyframes fadeInUp {
            from {
                opacity: 0;
                transform: translateY(20px);
            }
            to {
                opacity: 1;
                transform: translateY(0);
            }
        }

        @keyframes bounce {
            0%, 20%, 50%, 80%, 100% {
                transform: translateY(0);
            }
            40% {
                transform: translateY(-20px);
            }
            60% {
                transform: translateY(-10px);
            }
        }

        @media (max-width: 768px) {
            .hero h1 {
                font-size: 2.5rem;
            }
            .hero p {
                font-size: 1.1rem;
            }
            .projects-grid {
                grid-template-columns: 1fr;
                padding: 2rem 1rem;
            }
        }
    </style></head> <body> <div class=hero> <div class=hero-content> <h1></h1> <p></p> <div class=social-links> <a href=martincastro.10.5@gmail.com class=project-link target=_blank> <i class></i> martincastro.10.5@gmail.com </a> <a href=https://martincastroalvarez.com class=project-link target=_blank> <i class></i> martincastroalvarez.com </a> <a href=https://github.com/MartinCastroAlvarez class=project-link target=_blank> <i class></i> MartinCastroAlvarez </a> <a href=https://www.linkedin.com/in/martincastroalvarez/ class=project-link target=_blank> <i class></i> MartinCastroAlvarez </a> </div> </div> <div class=scroll-indicator> <i class="fas fa-chevron-down"></i> </div> </div> <div class=projects-grid> <div class=project-card> <h2>Deep Learning</h2> <p></p> <a href=https://github.com/MartinCastroAlvarez/langchain-virtual-assistant class=project-link target=_blank> <i class="fab fa-github"></i> langchain-virtual-assistant </a> <p>Engineered an AI-powered virtual assistant using LangChain and RAG, enabling context-aware conversations and document analysis with OpenAI&#39;s GPT models</p> <a href=https://github.com/MartinCastroAlvarez/llm-react-api class=project-link target=_blank> <i class="fab fa-github"></i> llm-react-api </a> <p>Developed a full-stack React application with Node.js backend, integrating OpenAI&#39;s GPT API for intelligent content generation and React Flow for interactive data visualization</p> <a href=https://github.com/MartinCastroAlvarez/sql-cursor-ai-agent class=project-link target=_blank> <i class="fab fa-github"></i> sql-cursor-ai-agent </a> <p>Built an intelligent SQL query builder using GPT-powered AI agents, enabling natural language to SQL conversion with React and Tailwind for an intuitive user interface</p> <a href=https://github.com/MartinCastroAlvarez/image-classification-transformer class=project-link target=_blank> <i class="fab fa-github"></i> image-classification-transformer </a> <p>Implemented state-of-the-art image classification using Vision Transformers (ViT), achieving high accuracy with PyTorch and comprehensive visualization using Matplotlib and Seaborn</p> <a href=https://github.com/MartinCastroAlvarez/higgs-boson-machine-learning class=project-link target=_blank> <i class="fab fa-github"></i> higgs-boson-machine-learning </a> <p>Developed advanced machine learning models to detect Higgs boson signals, utilizing scikit-learn for feature engineering and statistical analysis with comprehensive data visualization</p> <a href=https://github.com/MartinCastroAlvarez/langchain-agent-streamlit class=project-link target=_blank> <i class="fab fa-github"></i> langchain-agent-streamlit </a> <p>Created an interactive LLM agent using LangChain and Streamlit, enabling natural language processing and decision-making capabilities with OpenAI integration</p> <a href=https://github.com/MartinCastroAlvarez/gpt-context-injection class=project-link target=_blank> <i class="fab fa-github"></i> gpt-context-injection </a> <p>Engineered a context-aware GPT system implementing RAG techniques for enhanced response accuracy and domain-specific knowledge integration</p> <a href=https://github.com/MartinCastroAlvarez/html2vec class=project-link target=_blank> <i class="fab fa-github"></i> html2vec </a> <p>Engineered a custom NLP pipeline to extract structured data from noisy HTML using SpaCy, Keras, and rule-based NER — deployed for semantic document indexing</p> <a href=https://github.com/MartinCastroAlvarez/search-keras-gensim-elasticsearch class=project-link target=_blank> <i class="fab fa-github"></i> search-keras-gensim-elasticsearch </a> <p>Built a semantic search engine combining Word Embeddings (GloVe) with Elasticsearch, enabling efficient text similarity search and content recommendation</p> <a href=https://github.com/MartinCastroAlvarez/deep-age-classifier class=project-link target=_blank> <i class="fab fa-github"></i> deep-age-classifier </a> <p>Developed a CNN-based age detection system using Keras, implementing transfer learning for accurate facial age estimation with comprehensive data preprocessing</p> <a href=https://github.com/MartinCastroAlvarez/keras-nltk-topic-modeling class=project-link target=_blank> <i class="fab fa-github"></i> keras-nltk-topic-modeling </a> <p>Implemented neural network-based text classification using Keras and NLTK, enabling efficient topic modeling and document categorization</p> <a href=https://github.com/MartinCastroAlvarez/keras-document-classifier class=project-link target=_blank> <i class="fab fa-github"></i> keras-document-classifier </a> <p>Built an asynchronous document classification system using Keras, integrating Google Search API for enhanced context and real-time processing</p> <a href=https://github.com/MartinCastroAlvarez/keras-image-detection-classification class=project-link target=_blank> <i class="fab fa-github"></i> keras-image-detection-classification </a> <p>Developed a robust image detection and classification system using TensorFlow and Keras, implementing transfer learning for high-accuracy object recognition</p> <a href=https://github.com/MartinCastroAlvarez/python-recommender-systems class=project-link target=_blank> <i class="fab fa-github"></i> python-recommender-systems </a> <p>Created a fully serverless personalized recommendation engine with AWS Lambda, NumPy, and Algolia, delivering low-latency suggestions via collaborative filtering and novelty/diversity algorithms</p> <a href=https://github.com/MartinCastroAlvarez/graph-link-prediction class=project-link target=_blank> <i class="fab fa-github"></i> graph-link-prediction </a> <p>Engineered a deep learning system for link prediction in graph networks using Keras, enabling accurate relationship forecasting in complex networks</p> <a href=https://github.com/MartinCastroAlvarez/python-deep-learning-algorithms class=project-link target=_blank> <i class="fab fa-github"></i> python-deep-learning-algorithms </a> <p>Implemented advanced deep learning algorithms using Python, focusing on efficient numerical computing with NumPy and scientific computing with SciPy</p> <a href=https://github.com/MartinCastroAlvarez/cross-datasource-entity-matching class=project-link target=_blank> <i class="fab fa-github"></i> cross-datasource-entity-matching </a> <p>Developed a robust entity matching system for cross-dataset integration, implementing efficient data alignment and validation techniques</p> <a href=https://github.com/MartinCastroAlvarez/supply-chain-optimization class=project-link target=_blank> <i class="fab fa-github"></i> supply-chain-optimization </a> <p>Engineered a supply chain optimization system using Python and NumPy, implementing efficient algorithms for logistics and resource allocation</p> <a href=https://github.com/MartinCastroAlvarez/Python-Monte-Carlo-Simulator class=project-link target=_blank> <i class="fab fa-github"></i> Python-Monte-Carlo-Simulator </a> <p>Built a sophisticated Monte Carlo simulation framework using Python and SciPy, enabling complex probabilistic modeling and statistical analysis</p> <a href=https://github.com/MartinCastroAlvarez/statistical-distributions class=project-link target=_blank> <i class="fab fa-github"></i> statistical-distributions </a> <p>Developed a comprehensive statistical analysis toolkit using Python, implementing various probability distributions with SciPy and visualization with Matplotlib</p> <a href=https://github.com/MartinCastroAlvarez/Genetic-Paper class=project-link target=_blank> <i class="fab fa-github"></i> Genetic-Paper </a> <p>Implemented genetic algorithms with focus on algorithmic complexity analysis, enabling efficient optimization and problem-solving strategies</p> </div> <div class=project-card> <h2>Cloud Infrastructure</h2> <p></p> <a href=https://github.com/MartinCastroAlvarez/aws-sagemaker-cdk class=project-link target=_blank> <i class="fab fa-github"></i> aws-sagemaker-cdk </a> <p>Engineered a production-grade MLOps infrastructure using AWS CDK, enabling scalable deployment and monitoring of multiple LLM models on SageMaker</p> <a href=https://github.com/MartinCastroAlvarez/gcp-kubernetes class=project-link target=_blank> <i class="fab fa-github"></i> gcp-kubernetes </a> <p>Deployed and managed Kubernetes clusters on GCP, implementing container orchestration and microservices architecture for scalable applications</p> <a href=https://github.com/MartinCastroAlvarez/pyspark-docker class=project-link target=_blank> <i class="fab fa-github"></i> pyspark-docker </a> <p>Containerized PySpark applications using Docker, enabling reproducible and scalable big data processing pipelines</p> <a href=https://github.com/MartinCastroAlvarez/apache-hive-docker class=project-link target=_blank> <i class="fab fa-github"></i> apache-hive-docker </a> <p>Implemented containerized Hive data warehouse using Docker, enabling efficient SQL-like querying of large datasets</p> <a href=https://github.com/MartinCastroAlvarez/hadoop-hdfs-map-reduce-docker class=project-link target=_blank> <i class="fab fa-github"></i> hadoop-hdfs-map-reduce-docker </a> <p>Containerized Hadoop ecosystem with MapReduce, enabling distributed processing of large-scale datasets in a reproducible environment</p> <a href=https://github.com/MartinCastroAlvarez/hadoop-hdfs-kafka-docker class=project-link target=_blank> <i class="fab fa-github"></i> hadoop-hdfs-kafka-docker </a> <p>Deployed Kafka streaming platform with Hadoop integration using Docker, enabling real-time data processing and event streaming</p> <a href=https://github.com/MartinCastroAlvarez/hadoop-hdfs-hbase-docker class=project-link target=_blank> <i class="fab fa-github"></i> hadoop-hdfs-hbase-docker </a> <p>Containerized HBase database with Hadoop integration, enabling scalable NoSQL storage and real-time data access</p> <a href=https://github.com/MartinCastroAlvarez/sparkql class=project-link target=_blank> <i class="fab fa-github"></i> sparkql </a> <p>Developed efficient SparkSQL queries for big data processing, enabling complex data transformations and analytics</p> <a href=https://github.com/MartinCastroAlvarez/aws-django-ansible class=project-link target=_blank> <i class="fab fa-github"></i> aws-django-ansible </a> <p>Automated Django application deployment on AWS using Ansible and Terraform, implementing infrastructure as code and continuous deployment</p> <a href=https://github.com/MartinCastroAlvarez/grpc-python class=project-link target=_blank> <i class="fab fa-github"></i> grpc-python </a> <p>Implemented high-performance gRPC services in Python, enabling efficient microservices communication and streaming</p> <a href=https://github.com/MartinCastroAlvarez/terraform-aws-django class=project-link target=_blank> <i class="fab fa-github"></i> terraform-aws-django </a> <p>Engineered infrastructure as code for Django applications on AWS using Terraform, enabling reproducible and scalable deployments</p> <a href=https://github.com/MartinCastroAlvarez/aws-django-kubernetes class=project-link target=_blank> <i class="fab fa-github"></i> aws-django-kubernetes </a> <p>Deployed Django applications on AWS EKS, implementing container orchestration and microservices architecture</p> <a href=https://github.com/MartinCastroAlvarez/aws-networking-elastic-beanstalk-automation class=project-link target=_blank> <i class="fab fa-github"></i> aws-networking-elastic-beanstalk-automation </a> <p>Automated AWS infrastructure setup including networking, RDS, ElastiCache, and Elasticsearch for scalable Django applications</p> <a href=https://github.com/MartinCastroAlvarez/supervisor-python class=project-link target=_blank> <i class="fab fa-github"></i> supervisor-python </a> <p>Implemented process management for Python applications using Supervisord, ensuring reliable service operation and monitoring</p> <a href=https://github.com/MartinCastroAlvarez/Python-Splunk-CLI class=project-link target=_blank> <i class="fab fa-github"></i> Python-Splunk-CLI </a> <p>Developed Python integration with Splunk for log analysis and monitoring, enabling efficient log processing and visualization</p> <a href=https://github.com/MartinCastroAlvarez/filesystem-tools class=project-link target=_blank> <i class="fab fa-github"></i> filesystem-tools </a> <p>Engineered file system management tools with AWS S3 integration, enabling efficient cloud storage operations and automation</p> </div> <div class=project-card> <h2>Blockchain</h2> <p></p> <a href=https://github.com/MartinCastroAlvarez/real-estate-solidity-contract class=project-link target=_blank> <i class="fab fa-github"></i> real-estate-solidity-contract </a> <p>Developed secure and auditable real estate smart contracts in Solidity, implementing Merkle trees for efficient property verification</p> <a href=https://github.com/MartinCastroAlvarez/solidity-upgradeable-contract class=project-link target=_blank> <i class="fab fa-github"></i> solidity-upgradeable-contract </a> <p>Engineered upgradeable smart contracts with advanced access control using OpenZeppelin, enabling secure and maintainable blockchain applications</p> <a href=https://github.com/MartinCastroAlvarez/rust-alloy class=project-link target=_blank> <i class="fab fa-github"></i> rust-alloy </a> <p>Built a high-performance blockchain API using Rust, implementing async operations with Tokio and Warp, integrated with Alloy and Foundry for smart contract interaction</p> <a href=https://github.com/MartinCastroAlvarez/zk-trust class=project-link target=_blank> <i class="fab fa-github"></i> zk-trust </a> <p>Implemented zero-knowledge proof verification for ERC20 contracts, integrating with Etherscan and CoinMarketCap APIs for enhanced security</p> <a href=https://github.com/MartinCastroAlvarez/zk-proof class=project-link target=_blank> <i class="fab fa-github"></i> zk-proof </a> <p>Developed smart contracts with RISC Zero integration, enabling zero-knowledge proof verification for enhanced privacy and security</p> <a href=https://github.com/MartinCastroAlvarez/anvil-of-fury class=project-link target=_blank> <i class="fab fa-github"></i> anvil-of-fury </a> <p>Created a local Ethereum development environment using Anvil, enabling efficient smart contract testing and deployment</p> <a href=https://github.com/MartinCastroAlvarez/ethereum-solidity-contract class=project-link target=_blank> <i class="fab fa-github"></i> ethereum-solidity-contract </a> <p>Engineered production-grade smart contracts for the Ethereum network, implementing secure and gas-efficient Solidity code</p> <a href=https://github.com/MartinCastroAlvarez/django-multi-blockchain class=project-link target=_blank> <i class="fab fa-github"></i> django-multi-blockchain </a> <p>Architected a cross-chain distributed system for Django, enabling seamless interaction with multiple blockchain networks</p> <a href=https://github.com/MartinCastroAlvarez/solana-token-rust class=project-link target=_blank> <i class="fab fa-github"></i> solana-token-rust </a> <p>Developed Solana token and NFT programs using Rust, implementing secure and efficient blockchain applications</p> <a href=https://github.com/MartinCastroAlvarez/rust-ecopark class=project-link target=_blank> <i class="fab fa-github"></i> rust-ecopark </a> <p>Built a high-performance database application in Rust, implementing efficient MySQL queries and Docker containerization</p> </div> <div class=project-card> <h2>Backend</h2> <p></p> <a href=https://github.com/MartinCastroAlvarez/python-fastapi class=project-link target=_blank> <i class="fab fa-github"></i> python-fastapi </a> <p>Engineered a high-performance REST API using FastAPI, implementing async operations and automatic OpenAPI documentation</p> <a href=https://github.com/MartinCastroAlvarez/Python-Video-Processing class=project-link target=_blank> <i class="fab fa-github"></i> Python-Video-Processing </a> <p>Developed a video generation system using MoviePy and OpenCV, enabling efficient video processing and manipulation</p> <a href=https://github.com/MartinCastroAlvarez/media-tools class=project-link target=_blank> <i class="fab fa-github"></i> media-tools </a> <p>Built a video processing pipeline using FFMPEG, implementing efficient media conversion and manipulation through shell scripting</p> <a href=https://github.com/MartinCastroAlvarez/geo-django class=project-link target=_blank> <i class="fab fa-github"></i> geo-django </a> <p>Implemented geospatial applications using Django with PostGIS, enabling advanced location-based services and analytics</p> <a href=https://github.com/MartinCastroAlvarez/pandas-geo-analytics class=project-link target=_blank> <i class="fab fa-github"></i> pandas-geo-analytics </a> <p>Developed geospatial data analytics using Pandas, enabling efficient processing and analysis of location-based data</p> <a href=https://github.com/MartinCastroAlvarez/hexagonal-spring-boot class=project-link target=_blank> <i class="fab fa-github"></i> hexagonal-spring-boot </a> <p>Engineered a clean architecture application using Spring Boot and React, implementing hexagonal design patterns for maintainable code</p> <a href=https://github.com/MartinCastroAlvarez/node-typescript-pdf-renderer class=project-link target=_blank> <i class="fab fa-github"></i> node-typescript-pdf-renderer </a> <p>Built a PDF rendering service using TypeScript, enabling dynamic document generation and customization</p> <a href=https://github.com//ai-syntax-compiler class=project-link target=_blank> <i class="fab fa-github"></i> ai-syntax-compiler </a> <p>Developed a custom programming language compiler for data scientists, implementing lexical analysis and parsing using Bison and Lex</p> <a href=https://github.com/MartinCastroAlvarez/automata-python class=project-link target=_blank> <i class="fab fa-github"></i> automata-python </a> <p>Implemented various automata algorithms in Python, enabling efficient pattern matching and language processing</p> <a href=https://github.com/MartinCastroAlvarez/java-spring-boot class=project-link target=_blank> <i class="fab fa-github"></i> java-spring-boot </a> <p>Engineered enterprise applications using Spring Boot, implementing robust backend services and REST APIs</p> <a href=https://github.com/MartinCastroAlvarez/data-structures-java class=project-link target=_blank> <i class="fab fa-github"></i> data-structures-java </a> <p>Implemented efficient data structures in Java, focusing on performance optimization and algorithm complexity</p> <a href=https://github.com/MartinCastroAlvarez/django-data-analytics class=project-link target=_blank> <i class="fab fa-github"></i> django-data-analytics </a> <p>Built a comprehensive data analytics platform using Django, implementing PnL, LTV, and retention analysis</p> <a href=https://github.com/MartinCastroAlvarez/go-lang-app class=project-link target=_blank> <i class="fab fa-github"></i> go-lang-app </a> <p>Developed high-performance applications using Go, implementing concurrent processing and efficient resource utilization</p> <a href=https://github.com/MartinCastroAlvarez/django-cms class=project-link target=_blank> <i class="fab fa-github"></i> django-cms </a> <p>Engineered a content management system using Django 3, implementing custom templates and forms for dynamic content</p> <a href=https://github.com/MartinCastroAlvarez/flask-mongodb-celery-messaging-api class=project-link target=_blank> <i class="fab fa-github"></i> flask-mongodb-celery-messaging-api </a> <p>Built a scalable chat server using Flask, MongoDB, Redis, and Celery, enabling real-time messaging and asynchronous processing</p> <a href=https://github.com/MartinCastroAlvarez/python-s3-media-server class=project-link target=_blank> <i class="fab fa-github"></i> python-s3-media-server </a> <p>Developed a file server using Flask and PIL, implementing efficient image processing and S3 storage integration</p> <a href=https://github.com/MartinCastroAlvarez/python-chat-server-sockets class=project-link target=_blank> <i class="fab fa-github"></i> python-chat-server-sockets </a> <p>Engineered a real-time chat server using Python sockets, enabling efficient network communication and message handling</p> <a href=https://github.com/MartinCastroAlvarez/python-web-crawler class=project-link target=_blank> <i class="fab fa-github"></i> python-web-crawler </a> <p>Built an efficient web crawler in Python, implementing robust scraping and data extraction capabilities</p> <a href=https://github.com/MartinCastroAlvarez/Python-Google-Spreadsheets class=project-link target=_blank> <i class="fab fa-github"></i> Python-Google-Spreadsheets </a> <p>Developed Python integration with Google Spreadsheets, enabling automated data processing and analysis</p> <a href=https://github.com/MartinCastroAlvarez/software-patterns class=project-link target=_blank> <i class="fab fa-github"></i> software-patterns </a> <p>Implemented various software design patterns in Python, demonstrating best practices for maintainable and scalable code</p> <a href=https://github.com/MartinCastroAlvarez/web-to-pdf class=project-link target=_blank> <i class="fab fa-github"></i> web-to-pdf </a> <p>Engineered web scraping tools using Python and Beautiful Soup, enabling efficient content extraction and PDF conversion</p> <a href=https://github.com/MartinCastroAlvarez/development-tools class=project-link target=_blank> <i class="fab fa-github"></i> development-tools </a> <p>Created comprehensive development tools for Python, Android, TypeScript, Django, Git, and GPT integration</p> <a href=https://github.com/MartinCastroAlvarez/python-jira-cli class=project-link target=_blank> <i class="fab fa-github"></i> python-jira-cli </a> <p>Developed Python integration with JIRA, enabling automated issue tracking and project management</p> </div> <div class=project-card> <h2>Frontend</h2> <p></p> <a href=https://github.com/MartinCastroAlvarez/microfrontends class=project-link target=_blank> <i class="fab fa-github"></i> microfrontends </a> <p>Architected a distributed frontend system using microfrontends, enabling scalable and maintainable web applications for enterprise</p> <a href=https://github.com/MartinCastroAlvarez/nextjs-app class=project-link target=_blank> <i class="fab fa-github"></i> nextjs-app </a> <p>Built a modern web application using Next.js, implementing server-side rendering and optimized performance</p> <a href=https://github.com/MartinCastroAlvarez/vuejs-app class=project-link target=_blank> <i class="fab fa-github"></i> vuejs-app </a> <p>Developed a responsive web application using Vue.js and TypeScript, implementing component-based architecture</p> <a href=https://github.com/MartinCastroAlvarez/svelte-app class=project-link target=_blank> <i class="fab fa-github"></i> svelte-app </a> <p>Engineered a high-performance web application using Svelte, implementing reactive programming and efficient DOM updates</p> <a href=https://github.com/MartinCastroAlvarez/react-typescript-app class=project-link target=_blank> <i class="fab fa-github"></i> react-typescript-app </a> <p>Built a type-safe React application using TypeScript, implementing modern frontend development practices</p> <a href=https://github.com/MartinCastroAlvarez/react-firebase-oauth class=project-link target=_blank> <i class="fab fa-github"></i> react-firebase-oauth </a> <p>Developed a secure React application with Firebase OAuth 2.0 integration, enabling robust authentication and authorization</p> <a href=https://github.com/MartinCastroAlvarez/flexbox-project class=project-link target=_blank> <i class="fab fa-github"></i> flexbox-project </a> <p>Implemented responsive layouts using CSS3 Flexbox, enabling modern and adaptive web design</p> <a href=https://github.com/MartinCastroAlvarez/typescript-map-reduce class=project-link target=_blank> <i class="fab fa-github"></i> typescript-map-reduce </a> <p>Engineered efficient data processing using TypeScript, implementing map-reduce patterns for large datasets</p> <a href=https://github.com/MartinCastroAlvarez/typescript-mongodb-nestjs-mvc class=project-link target=_blank> <i class="fab fa-github"></i> typescript-mongodb-nestjs-mvc </a> <p>Built a full-stack MVC application using TypeScript, MongoDB, and NestJS, implementing clean architecture principles</p> <a href=https://github.com/MartinCastroAlvarez/typescript-classes class=project-link target=_blank> <i class="fab fa-github"></i> typescript-classes </a> <p>Implemented object-oriented programming patterns in TypeScript, demonstrating advanced class design and inheritance</p> </div> <div class=project-card> <h2>Testing</h2> <p></p> <a href=https://github.com/MartinCastroAlvarez/cypress-tests class=project-link target=_blank> <i class="fab fa-github"></i> cypress-tests </a> <p>Developed comprehensive end-to-end testing suite using Cypress, enabling reliable frontend testing and automation</p> <a href=https://github.com/MartinCastroAlvarez/Flask-Application class=project-link target=_blank> <i class="fab fa-github"></i> Flask-Application </a> <p>Engineered a Flask REST API with 100% unit test coverage, implementing robust testing practices and continuous integration</p> <a href=https://github.com/MartinCastroAlvarez/javascript-selenium-web-driver class=project-link target=_blank> <i class="fab fa-github"></i> javascript-selenium-web-driver </a> <p>Built automated testing framework using Selenium WebDriver, enabling comprehensive browser-based testing</p> </div> <div class=project-card> <h2>Mobile</h2> <p></p> <a href=https://github.com/MartinCastroAlvarez/Python-Android-Manager class=project-link target=_blank> <i class="fab fa-github"></i> Python-Android-Manager </a> <p>Developed a web API for remote Android device emulator management, enabling efficient mobile testing and automation</p> <a href=https://github.com/MartinCastroAlvarez/UNLaM-Android-App class=project-link target=_blank> <i class="fab fa-github"></i> UNLaM-Android-App </a> <p>Engineered a native Android calendar application, implementing efficient data management and user interface</p> </div> <div class=project-card> <h2>Quantum Computing</h2> <p></p> <a href=https://github.com/MartinCastroAlvarez/quantum-algorithms-java class=project-link target=_blank> <i class="fab fa-github"></i> quantum-algorithms-java </a> <p>Implemented quantum computing algorithms in Java, enabling efficient quantum circuit simulation and analysis</p> <a href=https://github.com/MartinCastroAlvarez/assembly-logisim-circuits class=project-link target=_blank> <i class="fab fa-github"></i> assembly-logisim-circuits </a> <p>Developed digital logic circuits using Logisim, implementing assembly language programming and circuit simulation</p> </div> </div> <script>
        // Smooth scroll for the scroll indicator
        document.querySelector('.scroll-indicator').addEventListener('click', () => {
            document.querySelector('.projects-grid').scrollIntoView({ 
                behavior: 'smooth' 
            });
        });

        // Intersection Observer for fade-in animations
        const observer = new IntersectionObserver((entries) => {
            entries.forEach(entry => {
                if (entry.isIntersecting) {
                    entry.target.style.opacity = '1';
                    entry.target.style.transform = 'translateY(0)';
                }
            });
        }, {
            threshold: 0.1
        });

        document.querySelectorAll('.project-card').forEach(card => {
            card.style.opacity = '0';
            card.style.transform = 'translateY(20px)';
            card.style.transition = 'opacity 0.5s ease, transform 0.5s ease';
            observer.observe(card);
        });
    </script> </body> </html>