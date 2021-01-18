# Description

This is a bot to check availibility of rtx 3000 cards on EU sites. The program checks every 15 seconds for stocks in multiple sites.

Runs on:
Materiel.net
topachat.com
ldlc.com
pccomponentes.com
nvidia.com (for the FEs)

Compiled for windows with auto-py-to-exe : <https://github.com/brentvollebregt/auto-py-to-exe/>.

## Install

- Clone the Download the 'CompiledBot' Folder
- Install Firefox
- Install latest geckodriver.exe from <https://github.com/mozilla/geckodriver/releases> and unzip it into /CompileBot

## Use

- Run CompiledBot.exe

## Todo

- Add support for Alternate.be site

## From source

If you want to use the source code, you'll need : python >=3.6, geckodriver (in the same folder as main.py) and firefox installed.
As well as the python libraries: Selenium, lxml and requests. Then run 'python main_program.py' in your terminal.
