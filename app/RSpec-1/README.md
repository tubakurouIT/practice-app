# よく使われるマッチャー
- be_valid	有効であるか
- be_invalid	無効であるか
- include	配列に指定の値が含まれているか
- find	要素の検索を行う
- click	クリックを行う
- have_content	文字列が存在するか
- have_link	指定の値のリンクが存在するか
- eq	期待値と値を比較して一致するか
- have_selector	HTMLタグやCSSに指定の文字列が存在するか
- have_field	入力フォームが存在するか
- find_all	ページ上の指定のHTMLタグを全て取得する
- match	matchメソッドを使用して期待値と一致するか
- have_button	ページ上に指定のボタンが存在するか
- click_button	指定のボタンをクリックする
- have_current_path	パスを取得できる
- change	ある動作Aに対してBが変動するか


## エクスペクテーションとマッチャー(eq)

~~~
 describe '四則演算' do
  context '足し算' do
    it '1 + 1 は 2 になる' do
      expect(1 + 1).to eq 2
    end
  end
  context '足し算' do
    it '1 + 1 は 2 になる' do
      expect(1 + 1).to eq 3
    end
  end
end
~~~