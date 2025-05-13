# Disease Diagnosis using AI

This project is an AI-powered web application designed to assist in diagnosing ear-related diseases. It leverages machine learning models for image-based disease detection and provides a user-friendly interface for users to upload and analyze medical images.

---

## Features
- AI-powered disease diagnosis using a trained deep learning model.
- Simple and intuitive web interface built with Flask.
- Real-time predictions with a high level of accuracy.
- Easy deployment and scalability using platforms like Render or Heroku.

---

## Directory Structure
```
C:\Users\Mudda\Computer vission\diseasedignosis\
├── app.py                # Flask backend for the application
├── Procfile              # Deployment configuration file (used by Render/Heroku)
├── requirements.txt      # Python dependencies
├── runtime.txt           # Specifies the Python version
├── saved_model\          # Trained machine learning model (final_model.h5)
├── static\               # CSS and other static assets
│   ├── style.css
│   └── disease_info.json
├── templates\            # HTML templates for the web interface
│   ├── index.html
│   ├── results.html
```

---

## Installation

Follow these steps to set up the project locally:

1. Clone the repository:
   ```bash
   
   cd DiseaseDiagnosis
   ```

2. Install the required dependencies:
   ```bash
   pip install -r requirements.txt
   ```

3. Run the application:
   ```bash
   python app.py
   ```

4. Access the application in your browser:
   - Navigate to `http://127.0.0.1:5000` to use the interface.

---

## Deployment
To deploy the application on a platform like Render or Heroku:

1. Ensure your `Procfile`, `requirements.txt`, and `runtime.txt` are properly configured.
2. Push your project to a GitHub repository.
3. Connect your GitHub repository to Render or Heroku.
4. Follow the deployment steps provided by the chosen platform.

---

## Technologies Used
- **Python**: Programming language.
- **Flask**: Web framework.
- **TensorFlow**: Deep learning library.
- **HTML/CSS**: Frontend design.
- **Render**: Deployment platform.

---

## Contributing
Contributions are welcome! If you'd like to improve this project:
1. Fork the repository.
2. Create a new branch.
3. Submit a pull request with your changes.

---

## License
This project is open-source and available under the [MIT License](LICENSE).

---

## Contact
For questions or support, please reach out to:
- **Name**: Muddasir Khuwaja
- **Email**: engr.muddasir01@gmail.com
