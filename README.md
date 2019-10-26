# Execute_Time2
Same of Execute Time from jupyter_contrib_nbextensions, but with a timer

# Install
```bash
git clone https://github.com/luluperet/Execute_Time2 && cd Execute_Time2 && (jupyter nbextension install execute_time2 && jupyter nbextension enable execute_time2/ExecuteTime && cd ../  && rm -rf Execute_Time2 ) || (cd ../ && rm -rf Execute_Time2  && echo "PROBLEMS")
```
If not sudo
```bash
git clone https://github.com/luluperet/Execute_Time2 && cd Execute_Time2 && ( sudo -i jupyter nbextension install $PWD/execute_time2 && sudo -i jupyter nbextension enable execute_time2/ExecuteTime  && cd ../ rm -rf Execute_Time2) || ( cd ../  && rm -rf Execute_Time2 && echo "PROBLEMS")
```
