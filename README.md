##  Quick Start


### 1 Run the System
Process any match video and generate a commented broadcast:

```powershell
python run_standalone.py "path/to/your/match_video.mp4"
```

## Project Structure

- `run_standalone.py`: Main entry point for processing and playback.
- `services/worker/app/pipeline.py`: The core orchestration engine.
- `services/worker/app/nlp/`: Logic for narrative pacing and generation.
- `services/worker/app/utils/`: Utilities for video reconstruction and frame reading.
- `outputs/`: Where your final commented broadcasters are saved.