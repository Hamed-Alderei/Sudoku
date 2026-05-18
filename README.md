git status
git add .
git commit -m "before diff restore practice"

echo "// test diff and restore" >> MySudokuBoard.java

git diff MySudokuBoard.java
