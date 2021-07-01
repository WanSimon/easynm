```flowchart

st=>start: ca
op=>operation: op
cond=>condition: cond
input=>inputoutput: input
sub1=>subroutine: sub1
end=>end: end

st->op->cond
cond(yes)->input->end
cond(no)->sub1(right)->op
```
```

