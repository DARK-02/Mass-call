## FOR TERMUX USER

```bash
bash -c '''
clear
echo -e """
⌜                                              ⌝
 \e[31m╦\e[37m┌┐┌┌─┐┌┬┐┌─┐┬  ┬  ┌─┐┬─┐ |\e[36m» \e[37mScript: Installer
 \e[31m║\e[37m│││└─┐ │ ├─┤│  │  ├┤ ├┬┘ |\e[36m» \e[37mAuthor: DARK-02
 \e[31m╩\e[37m┘└┘└─┘ ┴ ┴ ┴┴─┘┴─┘└─┘┴└─ |\e[36m» \e[37mYoutube: MR_DARK
⌞                                              ⌟
"""
sleep 1
echo -e "\e[31m» \e[1;32mRunning"
sleep 1
apt install git -y
apt install python -y
apt install curl -y
cd
git clone https://github.com/DARK-02/Mass-call
cd Mass-call
pip3 install requests
python3 run.py
'''
``````
