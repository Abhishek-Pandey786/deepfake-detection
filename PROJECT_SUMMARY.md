# Deepfake Detection Project - Clean Version

## 📁 Essential Files Only

This project has been cleaned to include only the essential files needed for deepfake detection.

### Core Files:

- `deepfake.py` - Main training script
- `inference.py` - Model testing and inference
- `dataset_downloader.py` - Download real datasets
- `README.md` - Complete documentation
- `requirements.txt` - Python dependencies
- `.gitignore` - Git ignore rules

### Data Structure:

- `data/real_videos/` - Place authentic videos here
- `data/fake_videos/` - Place deepfake videos here
- `test_data/` - Place test samples here

### Auto-created During Training:

- `models/` - Saved model weights
- `results/` - Training plots and metrics

## Next Steps:

1. **Get Real Data**: `python dataset_downloader.py`
2. **Train Model**: `python deepfake.py`
3. **Test Model**: `python inference.py --input path/to/video.mp4 --visualize`

## Removed Unnecessary Files:

- ❌ `quick_setup.py` - Setup already complete
- ❌ `test_setup.py` - Initial verification done
- ❌ `__pycache__/` - Compiled Python files
- ❌ Empty placeholder directories
- ❌ Sample synthetic videos/images

The project is now clean, focused, and ready for real deepfake detection training! 🎯
