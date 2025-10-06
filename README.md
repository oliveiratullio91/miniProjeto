# Processamento de Imagens com Filtro Sépia em Paralelo
Projeto Python que demonstra processamento paralelo de imagens aplicando filtros sépia, comparando desempenho entre abordagens sequencial e paralela.

Sobre
Sistema de processamento de imagens que aplica filtros sépia utilizando múltiplas threads para melhorar performance. Inclui análise comparativa entre processamento sequencial e paralelo com métricas de speedup e eficiência.

Funcionalidades
Aplica efeito sépia em imagens

Processamento paralelo com múltiplas threads

Análise comparativa de desempenho

Sistema de logging com timestamps

Tratamento de erros e verificação de arquivos

Tecnologias
Python 3.13

OpenCV (processamento de imagens)

NumPy (manipulação de arrays)

Threading (paralelismo)

Instalação
bash
# Clone o repositório
git clone https://github.com/seu-usuario/miniProjeto.git
cd miniProjeto

# Crie ambiente virtual (recomendado)
python -m venv .venv
.venv\Scripts\activate  # Windows

# Instale dependências
pip install opencv-python numpy

Como Usar
Crie pasta images na raiz do projeto

Adicione suas imagens na pasta

Execute:

bash
python filtroImagens.py

Métricas
Speedup: Tempo_Sequencial / Tempo_Paralelo

Eficiência: Speedup / Número_de_Threads

Resultados típicos: 2-4x speedup com 2-4 threads.

## Desenvolvido por: Bárbara Portella, Tassiana Oliveira e Tullio Oliveira.
