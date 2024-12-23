
</head>
<body>
    <header>
        <h1>DX-Mamba: Exploring State Space Model for Dog X-ray Report Generation</h1>
    </header>
    <nav>
        <a href="#abstract">Abstract</a>
        <a href="#theme">DX-Mamba and state space model (SSM)</a>
        <a href="#overview">Overview</a>
    </nav>
    <main>
        <section id="abstract">
            <h2>Abstract</h2>
            <p>Thoracic diseases are common causes of canine deaths. Automatic medical imaging report generation aims to generate accurate and coherent reports for medical images to save manual labor for clinicians. Research in the past decade showed that deep learning approaches could achieve promising performance in assisting disease diagnoses with medical image interpretation in the medical field. However, the deep learning application for report generation in the veterinary field is limited. Also, deep learning models require a more comprehensive structure and a large amount of data for training to improve their diagnostic efficiency and accuracy in report generation. Therefore, in this paper, we first develop a large-scale dog thoracic X-ray images dataset, Dog-Xray, with 13,794 subject studies and 36,264 thoracic X-ray images between 2008 and 2024. We then propose a novel DX-Mamba model that combines a Mamba vision model for multimodal feature extraction, a triple attention alignment for multi-imaging and text feature alignment, a feature fusion state space model (FF-SSM) and a feature disentanglement state space model (FD-SSM) for comprehensive feature learning and disentanglement, and a prediction module for report generation. We also propose a novel report inter-class loss and an intra-class loss to ensure the compactness of similar report content within and among reports, for better report generation performance. Extensive experiment results show that our DX-Mamba model achieves state-of-the-art performance in the report generation task.</p>
        </section>
        <section id="theme">
            <h2>DX-Mamba and state space model (SSM) for report generation</a>
            <p>Automatic report generation for medical images aims to produce several descriptive sentences about medical images. Encoder-decoder architectures and retrieval augmented generation (RAG) methods have been applied to the automatic report generation task. However, the transformer-based methods as well as RAG are computationally expensive. In 2023, the Mamba model, leveraging the efficiency of selective state space models in compressing necessary information in smaller states, was proposed to address the computational inefficiency of transformers and local perception limitations of CNNs. In this research, we aim to use the powerful vision Mamba structure as the backbone and SSMs for feature fusion and disentanglement for the automatic report generation task. This page provides an overview of our proposed method. With extensive experiments, we show that our DX-Mamba model can be applied as an effective report generation model.  
             </p>
        </section>
        <section id="overview">
            <h2>Overview</h2>
        </section>
                
    </main>
    <footer>
        <p>&copy; 2024 Anonymous-ab. All rights reserved.</p>
    </footer>
</body>
</html>
