# AgriPredict AI - Crop Yield Prediction

A Flask-based web application that predicts crop yields using machine learning models.

## Project Structure

```
.
├── app.py              # Main Flask application
├── requirements.txt    # Python dependencies
├── vercel.json         # Vercel configuration
├── static/             # Static files
│   ├── data/          # JSON data files
│   └── images/        # Image assets
├── templates/          # HTML templates
└── README.md          # Project documentation
```

## Deployment Instructions

1. Install Node.js (required for Vercel CLI)
2. Install Vercel CLI:
   ```bash
   npm install -g vercel
   ```
3. Login to Vercel:
   ```bash
   vercel login
   ```
4. Deploy the application:
   ```bash
   vercel
   ```

## Required Files

- `dtr.pkl`: Decision Tree Regressor model
- `preprocessor.pkl`: Data preprocessor
- `static/data/regions.json`: Region data
- `static/data/crops.json`: Crop data

## Environment Variables

No environment variables are required for this deployment.

## API Endpoints

- `/`: Welcome page
- `/predictor`: Prediction interface
- `/api/predict`: Prediction API endpoint (POST)

## Dependencies

See `requirements.txt` for the complete list of Python dependencies. 