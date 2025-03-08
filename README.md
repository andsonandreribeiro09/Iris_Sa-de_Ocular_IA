# IRIS: 🔍 Inteligência Artificial e Leitura da Íris: O Futuro da Biometria? 👁️

## 📌 Sobre o Projeto
Bem-vindo ao **IRIS** – o sistema de inferência para reconhecimento de íris do projeto Worldcoin. Este é um pipeline avançado de reconhecimento de íris projetado para autenticação biométrica segura e eficiente. O sistema utiliza técnicas de **visão computacional** e **aprendizado de máquina** de última geração para garantir precisão e escalabilidade no reconhecimento biométrico.

### 🔍 O que é Reconhecimento de Íris?
O reconhecimento de íris é uma tecnologia biométrica poderosa que identifica indivíduos com base nos padrões únicos da íris do olho. O pacote **IRIS** visa tornar essa tecnologia acessível e promover avanços na área.

## 🚀 Principais Funcionalidades
✔ **Verificação em larga escala**: Capaz de validar a singularidade entre bilhões de usuários.
✔ **Segmentação precisa da íris**: Extração eficiente das regiões da íris para máxima acurácia.
✔ **Algoritmo de correspondência escalável**: Alto desempenho sem comprometer a precisão.
✔ **Integração intuitiva**: Fácil implementação em aplicações que exigem autenticação biométrica confiável.

## 🔬 Pipeline de Reconhecimento de Íris
O sistema segue um pipeline bem definido para garantir eficiência e precisão:

1️⃣ **Entrada da imagem da íris** – Fornece uma imagem da íris para verificação.  
2️⃣ **Segmentação da íris** – Identifica e isola a região da íris.  
3️⃣ **Extração de características** – Gera um template único com os padrões da íris.  
4️⃣ **Correspondência escalável** – Compara as características extraídas para verificar a singularidade.  
5️⃣ **Resultado** – Retorna a pontuação de confiança para autenticação segura e escalável.  

A Worldcoin utiliza essa tecnologia para validar identidades em ambientes desafiadores e garantir a exclusividade biométrica em larga escala.

---

## ⚡ Instalação Rápida
A instalação do pacote **IRIS** pode ser feita diretamente via **pip**:

```sh
pip install open-iris
```
**Opções de instalação:**
- **SERVER** – Para uso em máquinas locais.
- **ORB** – Para execução em dispositivos Orb.
- **DEV** – Para ambiente de desenvolvimento.

Após a instalação, verifique se o pacote foi instalado corretamente:

```sh
python3 -c "import iris; print(iris.__version__)"
```

---

## 🔄 Executando Inferência
Para realizar uma inferência básica, utilize o código abaixo:

```python
import cv2
import iris

# Criar objeto do pipeline IRIS
iris_pipeline = iris.IRISPipeline()

# Carregar imagem de entrada
img_pixels = cv2.imread("/path/to/ir/image", cv2.IMREAD_GRAYSCALE)

# Executar inferência
output = iris_pipeline(img_data=img_pixels, eye_side="left")
```

Para mais exemplos, confira nossos **notebooks de exemplo** na seção dedicada.

---

## 📁 Estrutura do Projeto

| Módulo               | Descrição |
|----------------------|------------------------------------------------|
| `iris`               | Pacote principal do sistema de reconhecimento de íris |
| `iris.callbacks`     | Callbacks para personalização da execução do pipeline |
| `iris.io`           | Classes e erros do fluxo de dados da pipeline |
| `iris.nodes`        | Implementação dos nós da pipeline |
| `iris.orchestration` | Mecanismos de orquestração do sistema |
| `iris.pipelines`    | Implementação do pipeline de reconhecimento |
| `iris.utils`        | Utilitários gerais do sistema e análise de saídas |

---

## 📄 Documentação
Para informações detalhadas, consulte.
