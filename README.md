## Usage

Mac:
```bash
mkdir -p ~/Library/texmf/tex/latex/
tar -C ~/Library/texmf/tex/latex/ -xvf shading.zip
./build
```
Ubuntu:
```bash
sudo apt install unzip texlive ghostscript
sudo mkdir -p /var/lib/texmf/tex/latex/
sudo unzip shading.zip -d /var/lib/texmf/tex/latex/
./build
```
The code above is built with the following template: http://www.davidgrant.ca/latex_resume_template
