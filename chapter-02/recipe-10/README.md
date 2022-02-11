### 流程图和时序图

#### 流程图

> \`\`\`flow
> st=>start: Start
> e=>end
> op=>operation: My Operation
> cond=>condition: Yes or No?
> 
> st->op->cond
> cond(yes)->e
> cond(no)->op
> \`\`\`

显示效果如下所示：

```flow
st=>start: Start
e=>end
op=>operation: My Operation
cond=>condition: Yes or No?

st->op->cond
cond(yes)->e
cond(no)->op
```

#### 时序图

> \`\`\`sequence
> Alice->Bob: Hello Bob, how are you?
> Note right of Bob: Bob thinks
> Bob-->Alice: I am good thanks!
> \`\`\`

显示效果如下所示：

```sequence
Alice->Bob: Hello Bob, how are you?
Note right of Bob: Bob thinks
Bob-->Alice: I am good thanks!
```

