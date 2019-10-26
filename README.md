# Execute_Time2
Same of Execute Time from jupyter_contrib_nbextensions, but with a timer

# Install
without sudo
```bash
git clone https://github.com/luluperet/Execute_Time2 && cd Execute_Time2 && { jupyter nbextension install execute_time2 && jupyter nbextension enable execute_time2/ExecuteTime && cd ../  && rm -rf Execute_Time2; } || { cd ../ && rm -rf Execute_Time2  && echo "--------->PROBLEMS<--------"; }
```
with sudo
```bash
git clone https://github.com/luluperet/Execute_Time2 && cd Execute_Time2 && { sudo -i jupyter nbextension install $PWD/execute_time2 && sudo -i jupyter nbextension enable execute_time2/ExecuteTime  && cd ../ rm -rf Execute_Time2 } || { cd ../  && rm -rf Execute_Time2 && echo "--------->PROBLEMS<--------"; }
```
