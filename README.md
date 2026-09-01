<div align="center">

<img src="https://capsule-render.vercel.app/api?type=waving&color=0:0D1117,50:12233b,100:16213e&height=200&section=header&text=Rian%20Ferreira&fontSize=58&fontAlignY=35&desc=ML%20Engineer%20%E2%80%A2%20Computer%20Vision%20%E2%80%A2%20MLOps&descSize=18&descAlignY=55&fontColor=ffffff" width="100%"/>

[![Typing SVG](https://readme-typing-svg.demolab.com?font=JetBrains+Mono&weight=500&size=22&duration=3000&pause=1000&color=58A6FF&center=true&vCenter=true&width=650&lines=Vis%C3%A3o+Computacional+da+pesquisa+%C3%A0+produ%C3%A7%C3%A3o;Pipelines+reprodut%C3%ADveis+%7C+MLOps+%7C+Cloud;Modelagem+bayesiana+e+NLP%2FOCR)](https://git.io/typing-svg)

<br>

[![Website](https://img.shields.io/badge/Website-bayes.ia.br-0A66C2?style=flat&logo=google-chrome&logoColor=white)](https://bayes.ia.br)
[![LinkedIn](https://img.shields.io/badge/LinkedIn-0A66C2?style=flat&logo=linkedin&logoColor=white)](https://linkedin.com/in/rian-ferreira)
[![GitHub](https://img.shields.io/badge/GitHub-181717?style=flat&logo=github&logoColor=white)](https://github.com/BayesTheory)

</div>

---

### Sobre

Engenheiro de Machine Learning com foco em Visão Computacional e NLP, atuando de P&D até produção ponta a ponta. Trabalho com pipelines reprodutíveis e robustos, deploy serverless com CI/CD e integração de soluções de OCR. Pesquisador pela **LAMCE/UFRJ**, atualmente na **Vox Radar**.

**Foco:** Computer Vision • NLP & OCR • MLOps e Cloud • Modelagem Bayesiana

---

### Tech Stack

<div align="center">

#### Linguagens
<p>
  <img src="https://skillicons.dev/icons?i=python,cpp,r,bash,latex" />
</p>

#### ML / Deep Learning
<p>
  <img src="https://skillicons.dev/icons?i=pytorch,tensorflow,sklearn,opencv" />
  <img src="https://huggingface.co/front/assets/huggingface_logo-noborder.svg" width="48" height="48" alt="HuggingFace"/>
</p>
<p>
  <code>Transformers</code> <code>RoBERTa</code> <code>LSTM</code> <code>XGBoost</code> <code>ARIMA</code> <code>Keras</code>
</p>

#### Computer Vision
<p>
  <img src="https://skillicons.dev/icons?i=opencv" />
  <img src="https://avatars.githubusercontent.com/u/53104118?s=48" width="48" height="48" alt="Roboflow" style="border-radius:8px"/>
</p>
<p>
  <code>YOLO</code> <code>Object Tracking</code> <code>Homografia</code> <code>PaddleOCR</code> <code>ICAO 9303 / MRZ</code> <code>Geometria Computacional</code>
</p>

#### NLP & LLM
<p>
  <img src="https://huggingface.co/front/assets/huggingface_logo-noborder.svg" width="48" height="48" alt="HuggingFace"/>
  <img src="https://avatars.githubusercontent.com/u/1342004?s=48" width="48" height="48" alt="Google" style="border-radius:8px"/>
</p>
<p>
  <code>GPT-2 / nanoGPT</code> <code>RoPE</code> <code>GQA</code> <code>SwiGLU</code> <code>FlashAttention</code> <code>Gemini API</code> <code>RAG</code>
</p>

#### Data Science
<p>
  <img src="https://raw.githubusercontent.com/devicons/devicon/master/icons/numpy/numpy-original.svg" width="48" height="48" alt="NumPy"/>
  <img src="https://raw.githubusercontent.com/devicons/devicon/master/icons/pandas/pandas-original.svg" width="48" height="48" alt="Pandas"/>
  <img src="https://raw.githubusercontent.com/devicons/devicon/master/icons/matplotlib/matplotlib-original.svg" width="48" height="48" alt="Matplotlib"/>
  <img src="https://raw.githubusercontent.com/devicons/devicon/master/icons/jupyter/jupyter-original.svg" width="48" height="48" alt="Jupyter"/>
</p>
<p>
  <code>Inferência Bayesiana</code> <code>Séries Temporais</code> <code>Detecção de Anomalias</code> <code>Drift Detection</code> <code>Feature Store</code>
</p>

#### Backend & DevOps
<p>
  <img src="https://skillicons.dev/icons?i=fastapi,docker,git,githubactions,linux,vscode" />
</p>
<p>
  <code>CI/CD</code> <code>DDD por camadas</code> <code>Testes automatizados</code> <code>Batch Processing</code>
</p>

#### Cloud & Dados
<p>
  <img src="https://skillicons.dev/icons?i=aws,gcp,firebase,postgres" />
</p>
<p>
  <code>Cloud Run</code> <code>AWS Lambda</code> <code>Firestore</code> <code>SQL</code>
</p>

</div>

---

### Projetos em Destaque

<table>
<tr>
<td width="50%" valign="top">

#### [Sentiment Analysis API](https://github.com/BayesTheory/Sentiment-Analysis-API)
API de análise de sentimentos pronta para produção

- RoBERTa servido via FastAPI
- Interface web integrada
- Logging estruturado no Firestore
- Containerizado com Docker
- Deploy no Google Cloud Run
- Pronto para escalar sob demanda

`Python` `FastAPI` `RoBERTa` `Docker` `Cloud Run` `Firestore`

</td>
<td width="50%" valign="top">

#### [Fraud Doc End-to-End](https://github.com/BayesTheory/Fraud-Doc-EndtoEnd)
Pipeline completo de detecção de fraude documental

- Quality gate de imagem com OpenCV
- Validação ICAO 9303 (checksums de MRZ)
- Extração de texto com PaddleOCR
- Batch processing sobre o MIDV-2020
- Arquitetura ponta a ponta reproduzível

`Python` `OpenCV` `PaddleOCR` `ICAO 9303` `MIDV-2020`

</td>
</tr>
<tr>
<td width="50%" valign="top">

#### [Eólica SCADA](https://github.com/BayesTheory/Eolica-Scada)
Monitoramento preditivo de turbinas eólicas

- Telemetria SCADA em arquitetura DDD por camadas
- Feature store sem skew treino/serving
- Detecção de anomalias com LSTM
- Previsão de potência com XGBoost e ARIMA
- Drift detection em produção
- Camada conversacional com Gemini API
- Deploy em Cloud Run

`LSTM` `XGBoost` `ARIMA` `Gemini API` `Cloud Run` `MLOps`

</td>
<td width="50%" valign="top">

#### [Vehicle Color Detector](https://github.com/BayesTheory/Vehicle-Color-Detector)
Detecção, tracking e classificação de cor de veículos

- Detecção com YOLO em tempo real
- Object tracking multi-veículo
- Classificação de 10 cores com 90%+ de acurácia
- Servido via FastAPI
- Aplicações em traffic monitoring
- Voltado a urban analytics e smart cities

`Python` `YOLO` `FastAPI` `Object Tracking` `Computer Vision`

</td>
</tr>
<tr>
<td width="50%" valign="top">

#### [GPT-2 Mod Arch](https://github.com/BayesTheory/GPT2-Mod-Arch)
nanoGPT modernizado com arquitetura de LLMs atuais

- Base no nanoGPT (GPT-2) de Karpathy
- Rotary Position Embeddings (RoPE)
- Grouped-Query Attention (GQA)
- Ativação SwiGLU
- FlashAttention para treino eficiente
- Implementado do zero em PyTorch

`PyTorch` `Transformers` `RoPE` `GQA` `SwiGLU` `FlashAttention`

</td>
<td width="50%" valign="top">

#### [Modern Speed Scanner](https://github.com/BayesTheory/Modern-Speed-Scanner)
Scanner de documentos com IA e geometria computacional

- Detecção automática de bordas do documento
- Correção de perspectiva por homografia
- Realce e binarização adaptativa
- Transforma qualquer foto em documento escaneado
- Pipeline leve, sem dependência de nuvem

`Python` `OpenCV` `Geometria Computacional` `Image Processing`

</td>
</tr>
</table>

---

### Áreas de Interesse

```
Computer Vision · NLP & OCR · MLOps · Modelagem Bayesiana
Cloud Pipelines · Data Engineering · Programação Probabilística
```

---

### Experiência & Pesquisa

| Onde | Papel |
|------|-------|
| **Vox Radar** | Engenheiro de Machine Learning em Visão Computacional |
| **LAMCE / COPPE — UFRJ** | Pesquisador — formação e projetos de P&D |

---

<div align="center">

### GitHub Stats

<img src="https://github-readme-stats.vercel.app/api?username=BayesTheory&show_icons=true&theme=github_dark&hide_border=true&bg_color=0d1117&title_color=58a6ff&icon_color=58a6ff&text_color=c9d1d9" height="165"/>
<img src="https://github-readme-streak-stats.herokuapp.com/?user=BayesTheory&theme=github-dark-blue&hide_border=true&background=0d1117&stroke=30363d&ring=58a6ff&fire=58a6ff&currStreakLabel=58a6ff" height="165"/>

<br>

<img src="https://github-readme-stats.vercel.app/api/top-langs/?username=BayesTheory&layout=compact&theme=github_dark&hide_border=true&bg_color=0d1117&title_color=58a6ff&text_color=c9d1d9&langs_count=8" height="165"/>

<br><br>

### Contribuições em 3D

<img src="https://raw.githubusercontent.com/BayesTheory/BayesTheory/main/profile-3d-contrib/profile-night-rainbow.svg" width="100%">

</div>

---

<div align="center">

### Vamos conversar

**Aberto a:** Computer Vision • MLOps & Cloud • NLP/OCR • Pesquisa Aplicada

<br>

[![Website](https://img.shields.io/badge/Portfolio-000?style=for-the-badge&logo=vercel&logoColor=white)](https://bayes.ia.br)
[![LinkedIn](https://img.shields.io/badge/LinkedIn-0A66C2?style=for-the-badge&logo=linkedin&logoColor=white)](https://linkedin.com/in/rian-ferreira)
[![GitHub](https://img.shields.io/badge/GitHub-181717?style=for-the-badge&logo=github&logoColor=white)](https://github.com/BayesTheory)

<br>

*"Precisão, performance e uma pitada de estética"*

<br>

<img src="https://komarev.com/ghpvc/?username=BayesTheory&color=58a6ff&style=flat&label=Profile+Views"/>

</div>

<img src="https://capsule-render.vercel.app/api?type=waving&color=0:0D1117,50:12233b,100:16213e&height=100&section=footer" width="100%"/>
