# API DOCUMENTATION:VERTANI(Green Farm)
Created ad Fahri Kurniawan As a Cloud Computing
#INSTALATION
1. git clone  {github repo}
2. python3 -m venv .venv
3. pip install - r requirements.txt

   ## Predict by Post
   - POST http://127.0.0.1:5001/pred
      >Method ini akan mengeluarkan response
      ```
         {

          "id": "abc123",

          "prediction": "Tanah terdeteksi",

          "suggested_crop": "Sawi",

          "reason": "Cocok ditanam di tanah lembab dengan pH netral.",

          "created_at": "2024-12-10 15:00:00"

         }



   - GET http://127.0.0.1:5001/history
