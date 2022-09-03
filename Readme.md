# 常用香港外字表

## 序言

科技由人用，技窮則變通。老外「磚家」曾言道：漢字不適應電腦，唯淘汰一途。今天，漢字游走電腦間，勃勃生氣。從「不適電腦」論，到字元編碼多家並行、互不兼容，到1980年代中期「Big5碼」一統正體中文電腦天下，再到今天的Unicode時代，沒有甚麼窮途。

但，這不等於惱人的麻煩事可休止。

Big5碼乃臺灣產物，用於香港，則缺「香港字」——實即「粵字」，粵語或粵地區常用字，包括在地用字、方言字、異體字等。缺「香港字」的中文系統，「深水埗」、「鰂魚涌」、「杏花邨」、「赤鱲角」、「鴨脷洲」等皆現空格，連本地地名也無法輸入，豈不惱哉！

1990年代，各家中文字庫廠商推出不同編碼的「香港字外字集」，在Big5碼擴充區增造粵字。空格雖塡回，卻再次上演「萬碼奔騰」。如華康784外字、全眞550外字，還有中國龍外字、國喬外字、中國海字集等，諸家編碼殊異。彼字集之「邨」字碼位，此字集收錄「埗」字。含「綠楊新邨」的電郵一send出，接收者看到「綠楊新埗」，差之何止毫釐。唯蒙納471香港補字集沿襲文鼎外字編碼，數家暢銷報章均使用蒙納字庫，才有少許共通處。但，據個人記憶，其普及率不及華康外字集。

這香港字互不兼容的局面，幾時給勒停？1995年，香港政府公開內部造字集，名「政府通用字庫」（Government Common Character Set，簡稱GCCS），收三千餘字，數量冠絕各家。但字集字形質素差劣，收字無章無序，古字、異體字、正字、訛俗字、錯字、重複字共冶一爐，亦爲人詬病。隨手偶拾，「𡚒」字何字？「奮」之誤寫也。「奮」的首與腹部，誤駁「舊」的足，成了畸胎。又如「𠎀」字，査遍大小字書均無所獲，疑爲「傑」字之訛，「舛」之左旁誤寫作「歺」也。再數「𨌺」字，字書所無，卻皆有「翰」字。蓋「𠦝」旁誤書「車」旁也。唯各廠商均希望及早結束「萬碼奔騰」之局，而此字集除了涵蓋各家造字外，更有官方性質，故諸家紛紛採之作標準。

平心而論，GCCS並非一文不值。一者，至少我打「翠林邨」，你不會看到「翠林脷」。二者，字集所收的部份異體，實乃正寫。有些漢字，如「者」、「青」等，在平時Big5碼中的字樣，經常是不正統的。多家字型廠商造字時，皆棄正從俗。我要麼不用該字型，要麼不能用正字。今我用造字技術，於GCCS異體碼位自行造字，「者」字用Big5擴充區的「8ECD」，不用原本的「AACC」，正統寫法的那一點回來了！不用與「老字頭」相混了！

晴天霹靂，1999年，GCCS易名作「香港增補字符集」（Hong Kong Supplementary Character Set，簡稱HKSCS），由「中文介面諮詢委員會」（簡稱「中諮會」）接手管理，字集增加到4000多字，卻取消了「者」部件、「青」部件、「爲」部件、「俞」部件、「眞」部件等正寫異體字！只是增收的字比過去靠譜一些，卻不代表過去收入的訛誤字會剔走。

版本更迭，最新版HKSCS收五千餘字，並已棄Big5投Unicode。對，隨着作業系統版本更新，是時候全球一同擁抱Unicode了。一眾「香港字外字集」完成歷史使命……才怪。因爲不少字型，還是只收錄了Big5的字元。要使粵字不缺，還得造字補完。然而，Unicode所收數萬漢字，要愚公移山式去製作，儼如以有涯隨無涯；即使HKSCS的五千餘字，若單靠個人獨力，也要絕塵閉關良久才可以完成。可別忘記，平日會用到的漢字才不過三四千，要造好一套HKSCS外字集，何不開發一套包含平日所用漢字的新字型？當初補完基本字體，如在下參與的「日和字集」、「開源香港常用中文字體計劃」等，尚有意思，可予人不缺字的基本字型。但若所有字型皆如此作法，殆矣！

如是者，《常用香港外字表》應運而生。一郎除了參與過不同的香港字補完計劃，工作時、工餘時皆與粵語書寫文本爲伍，也認識一些志同道合的朋友。本表乃一郎綜合個人及朋友之見，整理而成。從多個粵字表中，歸納篩選，期望去蕪存菁，壓縮造字字數，並爲收錄粵字分級，以方便參與造字工程的同道中人。

這表收錄日常生活裏會碰到的字，不論正字、本字，俗寫、異體，還是沒有其他字能取代的粵地區用字。所收的字，先分兩大部份：「見於Big5者」與「不見於Big5者」。前者字型也許已收錄，不必添補；後者則多數要動用人力。再依常見、常用程度，分作四等。這部份沒有作客觀的統計，僅憑個人及朋友的經驗來劃分。其中「不見於Big5者」的頭二等，又分「非異體字」和「異體字」兩種級別。「異體字」者，於Big5字元裏，或本字集非異體字元裏，已有替代寫法。雖然該異體寫法常見，但若用回替代寫法，也可以不造字。「非異體字」者，卻沒有替代字元，不造字不可。

由於本表僅憑個人之力，以經驗判斷而成，若有未逮，在所難免。如各位有異議，或看到一郎疏漏、訛謬之處，非常歡迎向在下提出，不吝賜正，以匡不逮。

## 說明

本表列出Big5編碼字集裏沒有收錄的常用香港字，以便進行Big5字型的增補工作。

本表綜合了數個較有系統、較有代表性或應用得較廣泛的香港外字集，並參照編者日常經驗，從中選出具代表性的香港字，依常用度進行分級。其結果並不是嚴謹統計，或會受編輯習慣影響。

編者建議工作人員依以下步驟進行增補工作：

1. 檢査字型裏A級至C級字元是否齊全，不全者應馬上補完。
2. 補完1級至5級字元。完成後可發佈，表示已「完成一般香港字補完工作」，此至字型應涵蓋九成以上會出現的字元。
3. 補完6級及ㄅ級字元。完成後絕大部份文件都不應再有漢字缺字問題。也可按使用者需求，才決定是否增補這兩級裏的哪些字。

## 字表
* [常用香港外字表　第1.7版　純文字檔案](suppchara.txt)
* [常用香港外字表　第1.7版　PDF檔案](suppchara.pdf)

## 版本
* 第1.7版：2020/09/17
* 第1.6版：2019/09/23
* 第1.5版：2018/12/24
* 第1.4版：2014/01/27
* 第1.3版：2013/12/01
* 第1.2版：2013/10/18
* 第1.1版：2013/09/21
* 第1.0版：2013/08/21

## 參考
* 香港中文界面資訊委員會：IICore香港特用字（229字）。參見張群顯：《IICore香港特用字音義試釋》http://hanzi.unihan.com.cn/downloads/【CDF5】IICore香港特用字音義試釋-张群显.pdf 。
* 饒秉才、歐陽覺亞、周無忌：〈廣州話特殊字表〉，《廣州話方言詞典（修訂版）》頁341-345。香港：商務，2009。
* 饒秉才、歐陽覺亞、周無忌：〈廣州話特殊字表〉，《廣州話方言詞典》頁377-380。香港：商務，1981。
* 華康字庫：華康784外字集 http://www.dynacw.com.tw/img/software/DFT_M3U.zip (已失效) 。
* 卓靈：〈香港字與內碼〉所附錄的「華康香港字字碼表」，《電腦時代》雜誌第119期，頁60。香港：電腦易出版集團，1995(?)。
* 蒙納字庫：蒙納471香港補字表 http://www.monotype.com.hk/download/sample_PDF/Monotype471.pdf 。
* 小郎、阿烈：日和字集 http://input.foruto.com/jptxt/fonteudc (已失效) 。
* Klneast：日和字集造字表（去除與HKSCS重覆部份），刊於「中文編碼網頁」http://code.web.idv.hk/charset/jpsakura.php 。
* 中國海：中國海字集。參見 高衡緒、林昌鑫：《中國海字集》。臺北：碁峰資訊，1992。
* 伍新華：95補充字集（第一版）。參見 伍新華：《視窗95造字》。香港：德嘉書業，1995(?)。
* 伍新華：95補充字集（第二版）。參見 伍新華：《中文電腦應用》。香港：德嘉書業，1998(?)。
* 伍新華：〈Big5碼已有的廣東話字〉，《中文電腦應用》頁235-236。香港：德嘉書業，1998(?)。
* 國喬173香港字。參見 伍新華：《倉頡輸入法用戶手冊》。香港：德嘉書業，1993，頁57-60。
* Klneast：香港某報章造字集，刊於「中文編碼網頁」http://code.web.idv.hk/charset/oncode.php 。
* Justfont：Justfont臺客語用字64字 https://www.facebook.com/groups/enjoyfonts/permalink/1182111018610438/?comment_id=1182114921943381&reply_comment_id=1182144075273799 。
* 粵語會館：72粵字敎學 http://www.yueyu.net (已失效) 。
*	編輯《粵語維基百科》時，於編輯區域下方「插入」特殊字符的欄中，選取「中文字」時所列出的粵字 https://zh-yue.wikipedia.org/w/index.php?title=Wikipedia:沙盤&action=edit 。

## 製作人員
* 編製：內木一郎

## 版權
* 本作品以[Creative Commons 署名 4.0授權條款](License.md)授權。
