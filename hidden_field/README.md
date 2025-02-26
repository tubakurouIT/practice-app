# hidden_field

 ~~~
 hidden_field は、フォーム内で下記のように使用することができこの場合だと
title というキーに対して楽しい Ruby という値を、ブラウザに表示することなく送ることが可能
 ~~~

 ~~~
 <%= f.hidden_field :title, :value => "楽しいRuby" %>
 ~~~

