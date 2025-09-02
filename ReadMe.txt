1. Open a bash terminal. At the bottom right, there should be a powershell terminal be default, just press the "+" icon and choose "Bash" option

2. Check python version with: py --version

3. Activate venv (virtual environment) so you don't waste memory space installing everything with: source .venv/Scripts/Activate
    You should see "(.venv)" immediately after every time you hit "enter" to know you're in venv
    To deactivate, type: deactivate

4. Install Django with: py -m pip install Django
    Update pip as well if you must
    Check Django version with the following:
        py 
        import django
        print(django.get_version())
        quit()

5. Run the page with: py manage.py runserver
    Stop the server with: CTRL + C

Git commands:
Pull:

mkdir folder_name
cd folder_name
git init
git remote add hw link
git pull hw main

	Ex:
	mkdir Homework_1
	git init
	git remote add hw1 https:...
	git pull hw1 main


Push:

git commit -am "comment"
git push hw main

	Ex:
	git commit -am "Completed HW"
	git push hw1 main

If no work, switch branches:
git checkout -b main
git push hw main
