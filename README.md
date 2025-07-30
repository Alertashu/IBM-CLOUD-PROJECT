# IBM-CLOUD-PROJECT
# Smart Farming Advisor AI Agent

An AI-powered assistant designed to support small-scale farmers with real-time, localized, and trusted agricultural guidance. Built using IBM watsonx.ai, IBM Granite foundation models, and document-based Retrieval-Augmented Generation (RAG). The agent can answer queries about crop recommendations, pest control, market prices, and weather advisories in English and local languages.

---

## Table of Contents
- [Project Overview](#project-overview)
- [Features](#features)
- [Technology Stack](#technology-stack)
- [Setup and Usage](#setup-and-usage)
- [Project Structure](#project-structure)
- [Contribution Guidelines](#contribution-guidelines)
- [License](#license)
- [Acknowledgements](#acknowledgements)

---

## Project Overview

Small-scale farmers often lack timely access to localized farming knowledge, increasing the risk of crop loss and lower income. This project leverages IBM’s cutting-edge AI platform to build an interactive agent that retrieves exact, trusted information by indexing agricultural advisories, crop guides, pest management documents, and market bulletins directly uploaded into IBM watsonx.ai.

Farmers can ask questions like “What crop suits my soil type in this season?” or “What is today’s mandi price for tomatoes?” and get clear, data-driven answers in their preferred language.

---

## Features

- **Localized advisories:** Supports questions based on official agricultural documents uploaded by the project team.
- **Multilingual support:** Granite multilingual foundation model enables responses in multiple local languages.
- **Document-based retrieval:** Uses vector indexing of PDFs, DOCX, and other document formats to ground answers in real knowledge base.
- **Contextual answers:** Provides precise answers backed by trusted sources, reducing misinformation.
- **Scalable deployment:** Deployable via API or web chat widget.

---

## Technology Stack

- **IBM watsonx.ai Studio & Agent Lab:** For building and configuring AI agents.
- **IBM Granite Foundation Models:** Powerful language models optimized for multilingual, enterprise-grade NLP.
- **Retrieval-Augmented Generation (RAG):** Enables the AI to provide answers grounded in uploaded agricultural documents.
- **IBM Cloud Object Storage:** Stores official documents and advisories accessed by the agent for answering queries.
- **Optional Integrations:** Weather or market price external APIs via custom tools.

---

## Setup and Usage

### Prerequisites

- IBM Cloud account with access to watsonx.ai Studio and Runtime.
- IBM Cloud Object Storage service provisioned.
- Official agricultural advisories, crop guides, etc., in PDF/DOCX format.

### Step-by-Step

1. **Upload Documents**  
   Upload your collection of agricultural documents (PDFs, Word docs) to your watsonx.ai project under the Assets/Data section.

2. **Create and Configure Agent**  
   - Launch Agent Lab via "Build an AI agent".  
   - Choose a Granite-13B or multilingual model.  
   - Add your uploaded documents as a knowledge base retrieval data source.  
   - Configure agent behavior with clear instructions and sample Q&A pairs.

3. **Index your Documents**  
   Allow the platform to vectorize your documents for retrieval. This may take several minutes.

4. **Test the Agent**  
   Use the preview chat to ask queries such as:  
   - "What pests affect tomatoes in Maharashtra?"  
   - "महाराष्ट्र में रबी के लिए कौन सी फसलें उपयुक्त हैं?"

5. **Deploy**  
   Deploy your agent as an API or chat widget and integrate it with your app or website.

---

## Project Structure

---

## Contribution Guidelines

Contributions from the community are welcome!  
- Fork the repository and create feature branches.  
- Ensure agricultural documents are official and well-formatted.  
- Report issues or suggest improvements via GitHub Issues.  
- Please maintain clear commit messages.

---

## License

MIT License - see the [LICENSE](LICENSE) file for details.

---

## Acknowledgements

- IBM for providing watsonx.ai and Granite models.  
- Indian Agricultural Research Council and State Agri Departments for official advisories.  
- Open source communities for document processing and vectorization tools.

---

If you have questions or want support with deployment or expanding the agent features, feel free to open an issue or contact the maintainers.

---

*Empowering farmers with AI-driven, trusted knowledge, one query at a time.*



