# Question Your Document Using Langchain

This Jupyter Notebook demonstrates how to use Langchain and a Hugging Face model to perform question answering (QA) on a local PDF document.

---

## 📄 Document Summary

The PDF file used in this example is named **`highway.pdf`** and contains the following text:

> "I went on my bucket list road trip all the way to the Arctic Ocean via Alaska Highway and Dempster Highway.  
> I live in Edmonton and always wanted to go there as Canada is the only country that has a public road to the Arctic Ocean.  
> I left on May 29, 2024, and returned home on June 12, 2024.  
> I went to Whitehorse via Stewart-Cassiar Highway and on my way back I took the Alaska Highway from Whitehorse."

---

## 🔍 Objective

The goal is to extract insights from the document using an NLP model with the Langchain framework.

**Use Case:**  
Ask the model:  
`"Where do I live?"`  
And the output should be:  
`"Edmonton"`

---

## 🛠️ Tech Stack

- **Langchain**
- **Hugging Face Transformers**
- **DistilBERT** (`distilbert-base-uncased-distilled-squad`)
- **PyPDF2** (for PDF text extraction)

---

## 🧠 Workflow

1. Read a PDF file using `PyPDF2`.
2. Extract text content from all pages.
3. Use Hugging Face's `pipeline()` with a pretrained QA model.
4. Wrap the pipeline with Langchain's `HuggingFacePipeline`.
5. Ask a question and get the answer based on the context of the document.

---

## 🚀 Sample Code Snippet

```python
pdf_path = r"C:\\Users\\Fawad\\highway.pdf"
context = read_pdf(pdf_path)
question = "where do I live?"
answer = answer_question_llm(context, question)
print(f"Answer: {answer}")
