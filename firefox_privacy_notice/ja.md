# Firefox ブラウザ　プライバシーに関する通知

2014年4月15日
{: datetime="2014-04-15" }

［この文書は、日本のFirefoxブラウザのユーザ等の便宜を図るために掲載している、Firefox Brower Privacy Noticeの参考訳です。］

Mozilla は、皆様のプライバシーを尊重します。Mozillaの[プライバシーポリシー](https://www.mozilla.org/privacy/)は、Mozilla（当社）（以下「Mozilla」といいます。）が Firefox から情報を受信する場合に、収集した情報をどのように取り扱うかについて、説明しています。


## 留意事項

Firefox は自動的に Mozilla および Mozilla のサービスプロバイダに接続し、更新、セキュリティ、スニペット（Snippets）、Firefox ヘルスレポートおよびその他機能を提供します。
{: #essential-features }

* ブラウザおよびアドオンの更新
  {: #auto-updates }

	ブラウザの更新：1 日に 1 度、Firefox は、ブラウザの更新を確認するため、Firefox のバージョン情報、優先言語、オペレーティングシステム（OS）およびバージョンに関する情報をMozillaに送信します。[以下の説明](https://support.mozilla.org/kb/how-stop-firefox-automatically-making-connections#w_auto-update-checking)に従うことにより、更新機能を無効にすることができますが、無効化することにより、セキュリティの脆弱性にさらされる可能性があります。

	アドオンのブロックリスト：1 日に 1 度、Firefox は、悪意のあるアドオンを確認するため、Mozilla に接続し、アドオン情報を確認します。これには、例えば、ブラウザのバージョン、OS およびそのバージョン、ロケール、合計要求回数、最終要求時間、要求日、IPアドレスおよびインストールされたアドオンのリストが含まれます。いつでも[メタデータの更新を無効](https://blog.mozilla.org/addons/how-to-opt-out-of-add-on-metadata-updates/)にすることができますが、無効化することにより、セキュリティの脆弱性にさらされる可能性があります。

* スニペット（Snippets）
  {: #snippets }

	Firefox の初期設定ホームページ（<about:home>）では、検索バーのすぐ下に、Mozilla が皆様にとって有益であると考える情報がロードされます。Mozilla はこれを「スニペット（Snippets）」と呼びます。１日に１度、Firefox は Mozilla に接続し、入手可能であれば、新しいスニペットを提供します。Mozilla は、スニペットがクリックされた回数、スニペットの名称、ブラウザのロケールおよび皆様がお使いの Firefox バージョンを収集します。

	関連するスニペットを表示させるため、Firefox は、皆様の IP アドレスを利用して、皆様の所在地を国レベルで調査するリクエストを月に一度 Mozilla に送信します。Mozilla は、かかる国レベルでの所在地情報を Firefox に返信し、この情報は Firefox のローカルに保存されます。Firefox は、ローカルに保存された国情報に基づき、皆様にお知らせするスニペットを選択します。

	Mozilla がスポンサーとなるスニペットの中には、相互対話的なものが含まれており、皆様がご自身の電話番号またはメールアドレスを共有することを選択できるようにするものがあります。たとえば、皆様は、Android に Firefox をインストールし、SMS を受信するため、ご自身の電話番号を入力することができます。皆様の個人情報は、Mozillaの電子メールおよび携帯端末マーケテイングベンダーによって受信され取り扱われます。

* Firefoxヘルスレポート
  {: #health-report .inproduct-link } 

	Firefox ヘルスレポート（FHR）は、ブラウザの安定性およびパフォーマンスに関する洞察ならびに度重なるクラッシュおよび遅い起動に遭遇する場合のサポートヒントを提供するため作成されます。Mozilla は、皆様が Firefox のパフォーマンスの変化を確認できるよう、皆様のデータを他の Firefox ユーザのデータとともに収集して情報統合し、皆様のブラウザに返信します。このデータには、例えば、デバイスハードウェア、オペレーティングシステム、Firefox のバージョン、アドオン（数および種類）、ブラウザイベント（browser event）の時期、レンダリング、セッションの復元、セッションの長さ、プロファイルの古さ、クラッシュの回数およびページ数が含まれます。FHR は、皆様が閲覧する URL 履歴を Mozilla に送信しません。

	Mozilla は、ブラウザのパフォーマンスに関する問題の分析および対処へのサポートなどの FHR の機能をユーザに提供するため、FHR を通じて送信されたデータを利用します。また Mozilla は、Firefox をより良いものにするため、FHR から得られたデータを収集して利用します。皆様は、[データシェア機能の無効化](https://support.mozilla.org/kb/firefox-health-report-understand-your-browser-perf#w_how-to-turn-data-sharing-on-or-off)を選択することができます。

* セキュリティ
  {: #security }

	Firefox は、悪意のあるまたは偽装されているウェブサイト、壊れているアドオンおよび第三者が発行するSSL 証明書を自動的にチェックします。

	安全なウェブサイト証明：安全なウェブサイト（すなわち「https」）を閲覧する際、Firefox はウェブサイトの証明書を認証します。これには、証明書によって指定される第三者のプロバイダとの通信が介される場合があります。Firefox は、この第三者に、情報を送信し、サイトの[証明書](https://support.mozilla.org/kb/secure-website-certificate)を特定します。皆様は[設定の変更](https://support.mozilla.org/kb/advanced-settings-browsing-network-updates-encryption#w_certificates-tab)を行うことができますが、オンライン認証機能を無効にすると、Firefox は皆様が閲覧するウェブサイトの同一性を確認することができません。本機能を無効にすることによって、皆様の個人情報が傍受される危険性が増大する場合があります。[接続の安全性を確認できない](https://support.mozilla.org/kb/connection-untrusted-error-message)場合、皆様は、Mozilla に対して、関連する証明書を送信することもできます。

	Firefox 偽装サイトおよび攻撃サイトからの防護：1 時間に 2 回、Firefox は、悪意のあるまたは偽装されているウェブサイトへのアクセスおよびダウンロードを防御するため、Google のセーフブラウジングリストをダウンロードします（Google のプライバシーポリシーはこちらです<https://www.google.com/policies/privacy/>）。このリストに記載されていないダウンロードされた実行ファイルについて、Firefoxは、かかるダウンロードに悪意があるかどうかを判断するため、セーフブラウジングサービスにメタデータを送信します。セーフブラウジング機能およびこの無効化に関する詳しい情報については、<https://support.mozilla.org/kb/how-does-phishing-and-malware-protection-work> をご覧ください。かかる機能が無効化される場合、Firefox は、違法または悪意のあるウェブサイトまたはダウンロードファイルである可能性を警告することができません。

* 使用統計情報の利用（リリースされていないビルドにおいては「Telementry」とも呼びます）
  {: #telemetry .inproduct-link}

	使用統計情報の利用または「Telemetry」は、ユーザインターフェース機能、メモリおよびハードウェアコンフィギュレーションの使用情報、パフォーマンスおよび応答性の統計を Mozilla に送信するFirefoxの機能です。皆様の IP アドレスも標準ウェブログ（web log）の一部として収集されます。使用統計情報は SSL を通じて送信され、Firefox の将来のバージョンを改良するために役立てられます。Mozilla に送信された使用統計情報は、集積統合され、Mozilla の従業員および一般の貢献者を含む幅広い開発者に公開されます。Telemetry が有効化されている場合、短期的な試みとして、ウェブサイト閲覧履歴に関する情報が収集される場合があります。

	本機能は、FirefoxのNightly、Developer Edition、Aurora および Beta ビルドにおいては、ユーザが Mozilla にフィードバックを提供するため、初期設定で有効化されています。Firefoxの通常リリース版においては、本機能は初期設定で無効化されています。

	Telementry およびその有効化または無効化に関する詳しい情報については、[こちら](https://support.mozilla.org/kb/send-performance-data-improve-firefox) にてご覧ください。

* タイル
	タイルとは、新しいタブページを開くと表示される Firefox の機能です。タイル機能を提供するため、Firefox は、クリック回数、インプレッション、IP アドレス、ロケール情報およびタイル特有のデータ（例：グリッドの位置およびサイズ）などのタイルに関連するデータを Mozilla に送信します。Firefox Beta においては、タイルのために実施されるTelemetryの短期的な試み（上記ご参照）として、広く閲覧されたドメインに関する情報が収集される場合があります。

* 既定検索エンジン
	皆様の所在地に最適な既定検索エンジンを選択できるよう、Firefox は、皆様の IP アドレスを利用して、皆様の所在地を国レベルで調査するリクエストを一度 Mozilla に送信します。Mozilla は、かかる国レベルでの所在地情報を Firefox に返信し、この情報は地域別に保存されます。Firefox は、地域別に保存された国情報に基づき、利用される既定検索エンジンを選択します。

---------------------------------------

また、リクエストがある場合、Firefox は、皆様に Sync、位置情報サービス、クラッシュレポートおよびアドオンなどの機能を皆様に提供するため、Mozilla に接続します。
{: #optional-features }

* **Sync**: [Firefox Sync](https://www.mozilla.org/firefox/sync/) は、皆様の Firefox ブックマーク、ブラウジング履歴、パスワードおよび皆様の全ての端末設定を同期化することができる機能です。Syncサービスをご利用になる場合、[Firefox Sync privacy notice](https://services.mozilla.com/privacy-policy/)をお読み頂くことができます。
{: #sync }

* **位置情報サービス**: Firefox には、サイトが皆様の位置情報をたずねる（例：サイトが地図上に皆様の現在地を表示できるようにする）ことができるようにする機能があります。サイトが皆様に位置情報をたずねる場合、Firefox は位置情報を確定および共有する前に、皆様に許可を求めます。位置情報を確定するため、Firefox は、オペレーティングシステムのジオロケーション機能、Wi-Fiネットワーク、携帯電話基地局またはIPアドレスを含む複数のデータを利用する場合があります。位置情報の推定にあたって、別途[プライバシーポリシー](https://www.google.com/privacy/lsf.html) が定められる GoogleのLocation Service にかかる情報が送信されます。
{: #location-services }

* **クラッシュレポート**: Firefox がクラッシュした場合、皆様は、Mozilla にクラッシュレポートを送信するかどうかを選択することができます。このレポートには、Mozilla が Firefox を改良するために必要なFirefoxがクラッシュした理由、クラッシュ時の有効なURL、クラッシュ中のコンピュータメモリ状態を含む技術情報が含まれます。Mozillaが受信するクラッシュレポートには、個人情報が含まれる場合があります。Mozilla は、クラッシュレポートの一部を <https://crash-stats.mozilla.com/> にて一般公開します。クラッシュレポートを一般公開する前に、Mozilla は、自動的な個人情報の編集を図ります。Mozilla は、皆様がコメント欄に記入できる内容については、これを編集しません。
{: #crash-reporter .inproduct-link }

* **SSL エラー**: 安全なウェブサイト接続が切断される場合、皆様は、エラーレポートを Mozilla に送信するかどうかを選択することができます。このレポートには、ウェブサイトの証明書および診断エラーコードが記録されます。かかる情報は、Mozilla が「特定された」ウェブサイトの証明書の有効性を監視し、また Mozilla ユーザへの潜在的なフィッシング攻撃を探知するのに役立てられます。

* **アドオン**: Firefox は、すでにインストールされているアドオンに基づき人気のあるアドオンの特集およびパーソナライズされたおすすめを表示するアドオンマネージャの Get Add-onsサイト (Get Add-ons pages) を提供します。パーソナライズされたおすすめを表示するため、Firefox はインストールされているアドオンのリスト、Firefox のバージョン情報および皆様の IP アドレスを含む情報を Mozilla に送信します。本送信は、Get Add-ons エリアがオープン（Open）である場合に限り行われ、[以下の説明](https://blog.mozilla.org/addons/how-to-opt-out-of-add-on-metadata-updates/)に従うことにより無効化することができます。Firefox のアドオンマネージャには、キーワードを入力することにより検索を実行できる検索バーがあり、Mozilla は、皆様におすすめを表示するために、キーワード検索、Firefox バージョン情報、ロケールおよび OS 情報を収集します。
{: #addons }
