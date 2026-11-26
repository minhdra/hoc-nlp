# Học NLP (tiếng Việt) từ đầu

Lộ trình cho người mới: NLP cổ điển → deep learning → Transformer/PhoBERT → LLM & RAG.
Mỗi bài là một notebook có giải thích khái niệm, ví dụ chạy được và bài tập.

| Thư mục | Nội dung | Trạng thái |
|---|---|---|
| `00-kiem-tra-moi-truong.ipynb` | Kiểm tra GPU, chạy thử PhoBERT | ✅ |
| `01-co-dien/` | Tiền xử lý, TF-IDF, phân loại văn bản | 🚧 bài 1 xong |
| `02-deep-learning/` | Embedding, RNN/LSTM, attention | ⏳ |
| `03-transformer/` | Transformer, fine-tune PhoBERT | ⏳ |
| `04-llm-rag/` | Prompt, RAG, LoRA | ⏳ |

## Chạy trên Kaggle / Colab
1. Kaggle: *File → Import Notebook → GitHub*, dán link repo (hoặc tải `.ipynb` rồi upload).
2. Bật **Internet** (Settings) để cài thư viện và tải model; bật **Accelerator → GPU** nếu cần.
3. Chạy ô `!pip install underthesea` ở đầu notebook.

## Chạy trên máy cá nhân
```bash
python -m venv .venv && source .venv/bin/activate
pip install -r requirements.txt   # GPU RTX 50xx: cài torch bản CUDA 12.8+
jupyter lab
```

Dữ liệu dùng trong repo là ví dụ tự viết hoặc dataset công khai.
