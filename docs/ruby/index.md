# Ruby スタイルガイド
## インデント
実はインデント幅を揃えると、コードは読みやすくなる。
インデントは水平タブ1つ。


**Bad**
```ruby
if cond
   -1
else
     1
end
```

**Good**
```ruby
if cond
	-1
else
	1
end
```

