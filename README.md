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
 ```
     {
    "history": [
        {
            "created_at": "2024-12-10 12:57:59",
            "id": "61b8c0d6-9207-4260-afc7-6d8887b02fa3",
            "prediction": "Tanah terdeteksi",
            "suggested_crop": "Tomat"
        },
        {
            "created_at": "2024-12-10 12:59:10",
            "id": "196ab5b7-1f9d-48d7-8008-cdaf1ecdb585",
            "prediction": "Tanah terdeteksi",
            "suggested_crop": "Terong"
        },
        {
            "created_at": "2024-12-10 13:00:07",
            "id": "78514de8-398b-459f-9190-02f6dba2e691",
            "prediction": "Tanah terdeteksi",
            "suggested_crop": "Sawi"
        },
        {
            "created_at": "2024-12-10 13:00:28",
            "id": "d1e59e8c-2122-4871-8ba5-fa84e0d74745",
            "prediction": "Tanah terdeteksi",
            "suggested_crop": "Tomat"
        }
       ]
   }
