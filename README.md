# dev_lab_docker

#docker build a "jp_w_pkg:v2" crawlable devenv image
#docker run --name jupyter_preinstall_pkgs -d -p 8888:8888 -v .:/home/jovyan/work -v $(pwd)/env1/:/home/jovyan/ jp_w_pkg:v2 start-notebook.sh --NotebookApp.token=''
