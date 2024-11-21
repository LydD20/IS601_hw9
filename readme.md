# Homework 9: API with QR Code
## Install
1. Cloned professor's repo
3. Make virtual environment:  python3 -m venv venv
4. Activate virtual environment: source venv/bin/activate
5. Install requirements: pip install -r requirements.txt
6. **IMPORTANT** run: mkdir qr_codes to create a qr codes directory to save in, permissions will be messed up and the docker container won't be able to write to the qr_codes directory if you don't.
7. Note: make sure docker is started
8. run pytest locally to check that it works locally
9. Start the app with docker compose up --build
10. Goto http://localhost/docs to view openapi spec documentation
11. Click "authorize" input username: admin password: secret
12. Test making,  retrieving, and deleting QR codes on the spec page.
