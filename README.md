# flowcharts-testing


```mermaid
graph LR
A[IN]-->B[System/Module]
B-->C[OUT]
style B fill:#ff,stroke:#333,stroke-width:4px
style A fill:#ffffff, stroke:#000, stroke-width:0px
style C fill:#ffffff, stroke:#000, stroke-width:0px
```


```flow
st=>start: Start:>http://www.google.com[blank]
e=>end:>http://www.google.com
op1=>operation: My Operation
sub1=>subroutine: My Subroutine
cond=>condition: Yes
or No?:>http://www.google.com
io=>inputoutput: catch something...
para=>parallel: parallel tasks

st->op1->cond
cond(yes)->io->e
cond(no)->para
para(path1, bottom)->sub1(right)->op1
para(path2, top)->op1
```


