This is basic project created for learing the basics of beautifulsoup , flask , huggingface and flutter which summarizes the content of a given url.

1. Make sure to copy the content of main.dart to your flutter project main.dart file(which you can find in 'lib' file).

2.Make sure flask (app.ipynb) is running in the background before launching the app.

3.To check if flask is properply running , open your cmd and type the following command

curl -X POST http://127.0.0.1:5000/summarize -H "Content-Type: application/json" -d '{"url":"http://example.com"}' if this gives the expected output then the flask server is running.
