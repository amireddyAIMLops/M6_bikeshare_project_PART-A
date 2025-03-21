FROM python:3.13.2
# Or any preferred Python version.
ADD main.py .
RUN pip install requests beautifulsoup4 python-dotenv
CMD [“python”, “./main.py”] 
# Or enter the name of your unique directory and parameter set.
#bike_sharing_api\app\main.py


#pip install -r .\bike_sharing_api\requirements.txt
#python.exe .\bike_sharing_api\app\main.py

#pip install -r requirements.txt
#python app\main.py

#docker build -t bkie_sharing_api_app .
#docker run -p 8080:80 bkie_sharing_api_app