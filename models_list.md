# VoxCPM2 Model Checkpoints Inventory

All models must be placed in `checkpoints/` (or `checkpoints/VoxCPM2/`) before running offline.

| Filename / Folder | Target Subpath | Upstream Source URL | Size | Purpose |
|---|---|---|---|---|
| `config.json` | `checkpoints/VoxCPM2/` | `https://huggingface.co/openbmb/VoxCPM2/resolve/main/config.json` | 2.1 KB | Model architecture configuration |
| `model.safetensors` | `checkpoints/VoxCPM2/` | `https://huggingface.co/openbmb/VoxCPM2/resolve/main/model.safetensors` | 4.2 GB | Main 2B DiT + MiniCPM-4 model weights |
| `audiovae.pth` | `checkpoints/VoxCPM2/` | `https://huggingface.co/openbmb/VoxCPM2/resolve/main/audiovae.pth` | 280 MB | DAC Audio VAE neural vocoder / encoder |
| `tokenizer.json` | `checkpoints/VoxCPM2/` | `https://huggingface.co/openbmb/VoxCPM2/resolve/main/tokenizer.json` | 1.8 MB | Tokenizer vocabulary & merge rules |
| `tokenizer_config.json` | `checkpoints/VoxCPM2/` | `https://huggingface.co/openbmb/VoxCPM2/resolve/main/tokenizer_config.json` | 1.2 KB | Tokenizer settings & special tokens |
| `special_tokens_map.json` | `checkpoints/VoxCPM2/` | `https://huggingface.co/openbmb/VoxCPM2/resolve/main/special_tokens_map.json` | 600 B | Special token mappings |
| `tokenization_voxcpm2.py` | `checkpoints/VoxCPM2/` | `https://huggingface.co/openbmb/VoxCPM2/resolve/main/tokenization_voxcpm2.py` | 15 KB | Tokenizer implementation |
