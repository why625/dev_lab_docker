# dev_lab_docker

#docker build a "jp_w_pkg:v1" crawlable devenv image
#docker run --name jupyter_preinstall_pkgs -d -p 8888:8888 -v $(pwd)/env1/:/home/jovyan/work jp_w_pkg:v1 start-notebook.sh --NotebookApp.token=''
