import os

env = Environment(ENV = os.environ, SHELL = '/bin/bash')
env.AppendENVPath('PATH', os.getcwd())
Decider('timestamp-newer')

checkFilesCMD = "ls -l"
env.Command(["log.txt"],[],checkFilesCMD)
