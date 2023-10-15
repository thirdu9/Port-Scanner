# SSH Bruteforcer

## Install required python packages
Open the CLI go to the current folder type to start the venv and install the required packages.
```
pip install -r requirements.txt
```

Open [`passwords.txt`](passwords.txt) file and add your passwords with the existing ones.

Use [**sshbrutethreaded.py**](sshbrutethreaded.py) if the taks is big and requires more computation power, for faster output.

---

## Running the program
Use 
```
python sshbrute.py
```
Enter '*Target Address*', '*SSH Username*' and '*passwords list file path*' (you can modify the [`passwords.txt`](passwords.txt) file or make your own file and input it's path here)

-
Same for `sshbrutethreaded.py`
