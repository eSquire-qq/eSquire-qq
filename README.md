Hi, i'm Artem 👋

I'm student of Poltava Poltava Polytechnic College, on the third course at the faculty Software Engineering.

💻 Study Experience

• EPAM Courses, Java Online Program (Spring-Summer 2022)

👦 About me

- 👀 I'm interested in reading programming literature.
- 🌱 I’m currently learning Java.
- 
[![My GitHub Stats](https://github-readme-stats.vercel.app/api/?username=eSquire-qq&count_private=true&theme=tokyonight&showicons=true)]()
[![My GitHub Language Stats](https://github-readme-stats.vercel.app/api/top-langs/?username=eSquire-qq&langs_count=5&theme=tokyonight)]()

# Create a folder under the drive root
$ mkdir actions-runner; cd actions-runner# Download the latest runner package
$ Invoke-WebRequest -Uri https://github.com/actions/runner/releases/download/v2.292.0/actions-runner-win-x64-2.292.0.zip -OutFile actions-runner-win-x64-2.292.0.zip# Optional: Validate the hash
$ if((Get-FileHash -Path actions-runner-win-x64-2.292.0.zip -Algorithm SHA256).Hash.ToUpper() -ne 'f27dae1413263e43f7416d719e0baf338c8d80a366fed849ecf5fffcec1e941f'.ToUpper()){ throw 'Computed checksum did not match' }# Extract the installer
$ Add-Type -AssemblyName System.IO.Compression.FileSystem ; [System.IO.Compression.ZipFile]::ExtractToDirectory("$PWD/actions-runner-win-x64-2.292.0.zip", "$PWD")

# Create the runner and start the configuration experience
$ ./config.cmd --url https://github.com/eSquire-qq/eSquire-qq --token AV3IELXG5FPBQ66I7WOUPADCTNJ7G# Run it!
$ ./run.cmd

runs-on: self-hosted


<!---
eSquire-qq/eSquire-qq is a ✨ special ✨ repository because its `README.md` (this file) appears on your GitHub profile.
You can click the Preview link to take a look at your changes.
--->
