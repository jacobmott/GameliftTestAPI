# GameliftTestAPI
My lambda code thats hosted in AWS behind an API gateway (For GameliftTest) 


![image](https://jacobmottgithub.s3.amazonaws.com/GameliftTestAPI/Screenshots/lambda-functions1.png)
![image](https://jacobmottgithub.s3.amazonaws.com/GameliftTestAPI/Screenshots/lambda-functions-screenshots-access1.png)

# Project Setup/Install instructions
The Content folder is not included as part of this project, if you want a copy of it, contact me @ vortexgamesemail@gmail.com


## For me
The content folder is stored in s3 bucket
Pull down from bucket
```
  aws s3 cp --recursive s3://<bucket>/GameliftTestAPI/Screenshots GameliftTestAPI/Screenshots
```

Push to bucket
```
  aws s3 cp --recursive GameliftTestAPI/Screenshots s3://<bucket>/GameliftTestAPI/Screenshots
```

Or just do a sync
```
  aws s3 sync GameliftTestAPI/Screenshots s3://<bucket>/GameliftTestAPI/Screenshots --delete
```
