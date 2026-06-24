# stroke-care-guide
# Comprehensive Stroke Care Guide: Prevention, Treatment, and Rehabilitation

## 1. Sobre o Projeto
Este repositório documenta um projeto de curadoria e síntese de informações médicas utilizando o **NotebookLM**. O objetivo é transformar documentos técnicos complexos sobre AVC em um guia prático, útil tanto para estudantes de saúde quanto para cuidadores domiciliares. O projeto foca em **Tradução de Conhecimento**, garantindo que a informação científica seja acessível, segura e humanizada.

## 2. Metodologia (Passo a Passo)

### 2.1 Curadoria de Fontes
As seguintes fontes foram selecionadas e processadas no NotebookLM para garantir a precisão clínica:
*   **[Fonte 1]:** *Diretrizes da Organização Mundial da Saúde (OMS) sobre Reabilitação Pós-AVC.*
*   **[Fonte 2]:** *Manual Prático de Assistência Domiciliar (Associação Brasileira de AVC).*
*   **[Fonte 3]:** *Protocolos de Prevenção Secundária de Acidente Vascular Cerebral.*
*(Nota: Os arquivos originais estão disponíveis na pasta `/docs` deste repositório).*

### 2.2 Estruturação dos Prompts (Dual-Track Prompting)
Desenvolvi prompts para filtrar as respostas de acordo com a persona:
*   **Perfil Profissional:** *"Atue como preceptor clínico. Extraia as diretrizes técnicas destas fontes para o manejo pós-AVC, utilizando terminologia técnica adequada e estruturando em protocolos clínicos."*
*   **Perfil Leigo/Cuidador:** *"Atue como um especialista em cuidado humanizado. Traduza os conceitos técnicos para linguagem simples e empática. Foque em passos práticos para o dia a dia e sinais de alerta imediatos."*

## 3. "Cicatrizes" (Troubleshooting & Aprendizados)
| Dificuldade | Ajuste (Troubleshooting) | Aprendizado |
| :--- | :--- | :--- |
| **Ambiguidade** | Apliquei restrições de escopo no System Prompt. | A IA exige limites claros para não misturar linguagens. |
| **Alucinação** | Adicionei a instrução: "Responda exclusivamente com base nas fontes". | Governança de IA é vital em temas sensíveis. |

## 4. Estrutura do Guia Final
O conteúdo gerado organiza-se em:
1. **Módulo Técnico:** Protocolos de reabilitação neurofuncional.
2. **Manual do Cuidador:** Rotina de assistência domiciliar.
3. **Matriz de Resposta Rápida:** Sinais de alerta (Tabela).

## 5. Estrutura do Repositório
Para garantir a reprodutibilidade e transparência do projeto, a estrutura está organizada da seguinte forma:

```text
/
├── README.md               # Documentação técnica e metodologia
├── /docs                   # Fontes originais (PDFs de diretrizes e manuais)
├── /prompts                # Arquivos .txt com os prompts refinados (Dual-Track)
└── /output                 # Resultados exportados do NotebookLM (Guias finais)

---

> **Disclaimer:** Este projeto é informativo. Não substitui consulta médica. Em caso de emergência, procure um hospital imediatamente.


👨‍💻 Author / Autor
Nonato Matondo Gabriel
Angola 🇦🇴
AI | Prompt Engineering | Data & Control Management
