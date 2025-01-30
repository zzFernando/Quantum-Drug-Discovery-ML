# 🚀 Quantum Drug Discovery with Machine Learning

Quantum Machine Learning (QML) aplicado à descoberta de fármacos, combinando aprendizado quântico e interpretabilidade. Este projeto utiliza **PennyLane** para computação quântica e **SHAP** para análise interpretável, permitindo a previsão da eficácia de compostos químicos.

---

## 📌 Visão Geral

🔬 **Objetivo**: Utilizar aprendizado de máquina quântico para prever a eficácia de moléculas no desenvolvimento de novos medicamentos, garantindo interpretabilidade das decisões do modelo.

💡 **Técnicas utilizadas**:
- Computação quântica com **PennyLane**
- Modelos híbridos **(quântico + clássico)**
- Técnicas de interpretabilidade com **SHAP**
- Treinamento e avaliação com **PyTorch e scikit-learn**

---

## 📂 Estrutura do Projeto

```
Quantum-Drug-Discovery-ML/
│── notebooks/                # Notebooks Jupyter para experimentos
│── src/                      # Código-fonte principal
│   │── quantum_model.py      # Definição do modelo quântico
│   │── train.py              # Script de treinamento
│   │── interpretability.py   # Implementação do SHAP
│── data/                     # Conjunto de dados (sintéticos ou reais)
│── results/                  # Resultados, gráficos e logs
│── requirements.txt          # Dependências do projeto
│── README.md                 # Documentação principal
│── LICENSE                   # Licença do projeto
└── .gitignore                # Arquivos ignorados pelo Git
```

---

## 🚀 Como Executar

### **1️⃣ Clone o Repositório**
```bash
git clone https://github.com/seu-usuario/Quantum-Drug-Discovery-ML.git
cd Quantum-Drug-Discovery-ML
```

### **2️⃣ Crie um Ambiente Virtual e Instale as Dependências**
```bash
python -m venv venv
source venv/bin/activate  # Linux/macOS
venv\Scripts\activate  # Windows

pip install -r requirements.txt
```

### **3️⃣ Execute o Treinamento do Modelo**
```bash
python src/train.py
```

### **4️⃣ Analise a Interpretabilidade**
```bash
python src/interpretability.py
```

### **5️⃣ (Opcional) Execute os Notebooks Interativos**
```bash
jupyter notebook notebooks/
```

---

## 📦 Dependências

Crie um arquivo **`requirements.txt`** com:
```plaintext
pennylane
scikit-learn
numpy
matplotlib
shap
torch
jupyter
```

---

## 📜 Licença

Este projeto é licenciado sob a **MIT License**.

---

📧 **Contato:** Para dúvidas ou sugestões, abra uma *issue* ou envie um e-mail para [fernando.kavinsky@ufrgs.br](mailto:fernando.kavinsky@ufrgs.br).
