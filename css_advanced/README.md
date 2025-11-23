
*{
  margin: 0;
  padding: 0;
  box-sizing: border-box;
}

body{
  display: flex;
  flex-direction: column;
  background: rgb(242, 243, 242);
}

main{
  display: flex;
  flex-direction: row;
  flex: auto;
}

article{
  flex: 2;
  overflow-y: auto;
}

aside{
  flex: 1;
  overflow-y: auto;
}
