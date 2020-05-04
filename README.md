# typelab2
<label> お名前 <span>(※)</span>
[text* nameval id:nameval class:form-control placeholder "山田　太郎"]</label>

<label> メールアドレス <span>(※)</span>
[email* emailval id:mailval class:form-control placeholder "example@gmail.com"]</label>

<label> メールアドレス確認 <span>(※)</span>
[email* emaiconfirm id:mailval2 class:form-control placeholder "example@gmail.com"]</label>

<label> 紹介者
[text introducerval id:inrtoducerval class:form-control placeholder "鈴木　太郎"]</label>

<label> 電話番号
[tel telval id:telval class:form-control placeholder "090-0000-0000"]</label>

<label> お問い合わせ種目
[select menu id:menuval class:form-control include_blank "1.チームワークサポート" "2.営業サポート" "3.コミュニケーションサポート" "4.個人コーチング"]</label>

<label> お問い合わせ内容 <span>(※)</span>
[textarea* inquiryid:textval class:form-control]</label>

[submit class:btn class:btn-primary class:btn-submit "送信"]
