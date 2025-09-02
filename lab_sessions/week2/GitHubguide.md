# Simple GitHub guide for IN4080 


In this course we are using GitHub to distribute the mandatory assignments and the material for the lab sessions. 

You find the course repository on GitHub here: https://github.uio.no/IN4080/2025/tree/main 

You can either download the files as a zip file, or clone the repository to your computer.

Here is a small and simple guide to how to download the files. 

## Download as zip (simplest)

Go to the repository: https://github.uio.no/IN4080/2025/

Click the green Code button -> Download ZIP.
Extract the folder on your computer.

## or Clone repository (less simple)
Cloning and pulling is recommended if you are comfortable with Git basics.

To clone the repository, use the following command:

```bash
git clone https://github.uio.no/IN4080/2025.git
```

The repository will be updated weekly with new material or assignments. 
To get the new files on your computer, use the following command: 

```bash
cd 2025          # go into the course folder
git pull origin main

```
This will download all the latest changes.


### Common problem
If you have changed the files locally (for example, added your solutions inside the repository), git pull may give a merge conflict. 

### Avoid common problem: Keep your own work in a separate folder 

Do **not** edit your solutions directly in the cloned repository. 
Instead, copy the assignment files to a separate folder where you keep your own work.


<details>
<summary>How to </summary>

- Download the repo (zip or clone).
- Copy the assignment files to your own folder (e.g. IN4080_username/).
- Do your work in your own folder. 
- When new material is published, just re-download the repo (zip or pull), without worrying about overwriting your work.

- Then you can always update the original repository safely.
If you just want to reset and start fresh, you can delete the old folder and clone the repository again.
</details>