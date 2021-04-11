# BlindScan

## Inspiration

I recently traveled to India and while I was there, I volunteered at a school for the blind. I saw that they did not have very many resources or specialized instructors to help them that do things such as reading. So, I decided to solve that problem through my knowledge of computer science.

## What it does

Essentially, my project is a document scanning app that is optimized to be used by the blind. It detects document borders and angles in real-time to give simple auditory instructions such as "move phone slightly to the left". After uploading the scanned image, the backend script processes the image and records all detected text, after which, it uses a text-to-speech algorithm to read the text to the user.

## How we built it

The document scanning feature is built using PWA, Scanner.js, and the backend text-to-speech algorithm to speak the instructions for scanning to the user. The image processing is done using a special deep learning OCR model that is tuned for processing images of small books and textbooks. 

The backend is built with flask.
