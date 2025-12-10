# test-repo
test repo for github
for i in {2..25}; do
  echo "Line $i" >> app.txt
  git add app.txt
  git commit -m "Update line $i"
done
