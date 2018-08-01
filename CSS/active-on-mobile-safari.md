###	Active on Mobile Safari

모바일 Safari 브라우저에서 .div:active 효과가 생기지 않아서 찾아보니, :active 자체를 Safari에서는 무시한다고 함. 그에 대한 대안으로 해당 엘레먼트에 다음과 같이 스타일하면 완벽하진 않지만 작동함.

```css
.divToActive {
  -webkit-tap-highlight-color: #ddd;
}

.divToActive:active {
  background-color: #ddd;
}
```

