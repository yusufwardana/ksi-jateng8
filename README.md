# KSI 2O25 - Jateng 8🧠📹

**TodoList Materi**

[![License: MIT](https://img.shields.io/badge/License-MIT-yellow.svg)](https://opensource.org/licenses/MIT)
[![Python 3.8+](https://img.shields.io/badge/python-3.8+-blue.svg)](https://www.python.org/downloads/)

## 🎥 Bumper Opening

https://github.com/user-attachments/assets/ec550e93-e9c4-459f-a8a1-46e122b5851e

## ✨ Key Features

- 🎥 **Video-as-Database**: Store millions of text chunks in a single MP4 file
- 🔍 **Semantic Search**: Find relevant content using natural language queries
- 💬 **Built-in Chat**: Conversational interface with context-aware responses
- 📚 **PDF Support**: Direct import and indexing of PDF documents
- 🚀 **Fast Retrieval**: Sub-second search across massive datasets
- 💾 **Efficient Storage**: 10x compression compared to traditional databases
- 🔌 **Pluggable LLMs**: Works with OpenAI, Anthropic, or local models
- 🌐 **Offline-First**: No internet required after video generation
- 🔧 **Simple API**: Get started with just 3 lines of code

## 🎯 Use Cases

- **📖 Digital Libraries**: Index thousands of books in a single video file
- **🎓 Educational Content**: Create searchable video memories of course materials
- **📰 News Archives**: Compress years of articles into manageable video databases
- **💼 Corporate Knowledge**: Build company-wide searchable knowledge bases
- **🔬 Research Papers**: Quick semantic search across scientific literature
- **📝 Personal Notes**: Transform your notes into a searchable AI assistant



### Video Optimization
```python
# For maximum compression
encoder.build_video(
    "compressed.mp4",
    "index.json",
    fps=60,  # More frames per second
    frame_size=256,  # Smaller frames
    video_codec='h265',  # Better compression
    crf=28  # Compression quality (lower = better quality)
)
```

### Distributed Processing
```python
# Process large datasets in parallel
encoder = MemvidEncoder(n_workers=8)
encoder.add_chunks_parallel(massive_chunk_list)
```

## 🐛 Troubleshooting

### Common Issues

**ModuleNotFoundError: No module named 'memvid'**
```bash
# Make sure you're using the right Python
which python  # Should show your virtual environment path
# If not, activate your virtual environment:
source venv/bin/activate  # On Windows: venv\Scripts\activate
```

## 🤝 Contributing

We welcome contributions! Please see our [Contributing Guide](CONTRIBUTING.md) for details.

```bash
# Run tests
pytest tests/

# Run with coverage
pytest --cov=memvid tests/

```

## 🆚 Comparison with Traditional Solutions

| Feature | Memvid | Vector DBs | Traditional DBs |
|---------|--------|------------|-----------------|
| Storage Efficiency | ⭐⭐⭐⭐⭐ | ⭐⭐ | ⭐⭐⭐ |
| Setup Complexity | Simple | Complex | Complex |
| Semantic Search | ✅ | ✅ | ❌ |
| Offline Usage | ✅ | ❌ | ✅ |
| Portability | File-based | Server-based | Server-based |
| Scalability | Millions | Millions | Billions |
| Cost | Free | $$$$ | $$$ |

## 📄 License

MIT License - see [LICENSE](LICENSE) file for details.

## 🙏 Acknowledgments

Created by [yusufwardana](https://github.com/yusufwardana)

Built with ❤️ using:
- [sentence-transformers](https://www.sbert.net/) - State-of-the-art embeddings for semantic search
- [OpenCV](https://opencv.org/) - Computer vision and video processing
- [qrcode](https://github.com/lincolnloop/python-qrcode) - QR code generation
- [FAISS](https://github.com/facebookresearch/faiss) - Efficient similarity search
- [PyPDF2](https://github.com/py-pdf/pypdf) - PDF text extraction

Special thanks to all contributors
