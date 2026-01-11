pkg update -y 
pkg install git python -y
git clone https://github.com/upsdelivery936-eng/Qingtricker.git 
cd QingTool 
pip install requests bs4 rich 
python qing_tool.py
