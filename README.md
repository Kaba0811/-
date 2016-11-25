# -
就活サイトのフォーム記入を簡単にするために作りました。Nortonを使ったフォーム記入の一部に対応しています。メリットとしては「フォーム記入ミスの低減」「時間短縮」などが挙げられます。適宜修正して使ってください。

javascript:(function(d, i, v) {    
  d[i]("name")[v] = "名前";
  d[i]("kana")[v] = "ひらがな";
  d[i]("sex")[v] = "性別";
  d[i]("seinengappi")[v] = "生年月日";
  d[i]("school")[v] = "学校名";     
  d[i]("mail")[v] = "メールアドレス";    
  d[i]("mail_chk")[v] = "メールアドレス";   
  d[i]("tel")[v] = "電話番号";
  d[i]("requireFields").submit();
})(document, "getElementById" ,"value");
