# multi-contributor-demo

git clone https://github.com/your-username/multi-contributor-demo.git
cd multi-contributor-demo


git pull

echo "Feature by User B" >> file.txt
git add .
git commit -m "Added feature B"
git push


echo "Line edited by B" > conflict.txt
git add .
git commit -m "B edit"
git push

