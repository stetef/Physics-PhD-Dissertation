# Information Content and Analysis of X-ray Absorption Spectroscopy and X-ray Emission Spectroscopy Using Machine Learning

**Samantha Tetef**

*Chair of the Supervisory Committee:* Professor Gerald T. Seidler, Physics

Data science and machine learning (ML) methods are revolutionizing scientific analysis and data processing. As a case in point, ML applied to X-ray spectroscopies has recently exploded, showcasing its effectiveness in fields such as electrical energy storage and chemical catalysis. Here, I include comprehensive computational studies of ML techniques applied to X-ray spectra, including X-ray absorption near edge structure (XANES) and valence-to-core X-ray emission spectra (VtC-XES). First, I utilized unsupervised ML to extract import chemical fingerprints and information content in sulforganics and phosphorganics. We compared different unsupervised ML techniques, namely principal component analysis (PCA), variational autoencoder (VAE), t-distributed stochastic neighbor embedding (t-SNE), and uniform manifold approximation and projection (UMAP). Additionally, we developed open-source tools for future researchers to utilize, including an API that interacts with PubChem to efficiently download and store metadata. Next, I used ML to improve the reliability of data analysis and decrease computational time in the context of imaging XANES experiments. To do so, we utilized dimensionality reduction and clustering to perform image segmentation and then identified phase composition using linear combination fitting. By decoupling the domain identification from the phase identification, we provided a more robust way to handle noise that was not reliant on obtaining appropriate linear combination fitting results. Finally, I used feature selection to speed up high-throughput experimental design. Specifically, we used Recursive Feature Elimination to select the most important energies in XANES spectra to measure in the context of a reference library. Then we demonstrated appropriate analysis on these reduced-energy spectra using a nano-XANES image. All these approaches and tools are broadly applicable to X-ray spectroscopy on other systems or using other spectroscopy techniques.
