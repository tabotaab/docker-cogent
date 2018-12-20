# How to run docker-cogent-cupcake

# First option :
*> docker run -v /yourdatadir:/data --rm -it cogent*

add your command to /opt/start , for example:

*> echo -e "run_mash.py --version" >> /opt/start*

run:

*> /opt/start*

# Second option:
*> docker run -v /yourdatadir:/data --rm -it cogent*

first run:

*> source /anaconda3/bin/activate anaCogent*

*> export LD_LIBRARY_PATH=$LD_LIBRARY_PATH:/Cogent/Complete-Striped-Smith-Waterman-Library/src*

*> export PYTHONPATH=$PYTHONPATH:/Cogent/Complete-Striped-Smith-Waterman-Library/src*

and then run your own commands.

# Docker repository:
https://hub.docker.com/r/tabotaab/docker-cogent-cupcake
