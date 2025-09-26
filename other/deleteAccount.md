# アカウント削除およびデータ削除について
[English below](#account-deletion-and-data-retention)

## 1. アカウント削除の手続き

本アプリのアカウント削除および関連するデータの削除をご希望される場合は、下記の手順に従ってご連絡ください。

### 削除リクエスト方法

アカウント削除をご希望の方は、以下の情報を添えて、アプリ開発者（Jiro Takita）のメールアドレスまでご連絡ください。

* **宛先メールアドレス**: **`takijiro0925@gmail.com`**
* **件名**: アカウント削除希望
* **本文に記載いただく情報**:
    1.  **アカウントに使用しているユーザーのメールアドレス**: （必須）
    2.  **現在のニックネーム（ユーザー名）**: （必須）

このメールを受け取り次第、ご本人確認と削除手続きを進めさせていただきます。手続きには数日かかる場合がございますので、あらかじめご了承ください。

---

## 2. 削除されるデータと保持期間

アカウント削除をリクエストされた場合、以下のデータが削除されます。

### 削除されるデータ

アカウント削除が完了すると、以下のデータは本アプリのデータベースから**完全に削除**されます。

* **ユーザーの認証情報**: （Firebase等で管理しているユーザーID、認証用メールアドレス）
* **ニックネーム（ユーザー名）**
* **ユーザーが作成したショッピングリストのデータ**: （リスト名、アイテム、チェック状況など）

### 保持されるデータと保持期間

法令遵守、不正行為の防止、およびアプリの安定性維持のため、以下のデータの一部またはすべては、アカウント削除後も**一定期間保持**される場合があります。

| データ種別 | 保持期間 | 保持理由 |
| :--- | :--- | :--- |
| **クラッシュレポート・利用状況ログ** | 最長90日間 | サービス品質の維持と不具合解析のため。データは匿名化されます。 |
| **法令遵守に関連する記録** | 法令が定める期間 | 不正利用の調査や法的な義務を果たすため。 |

これらの保持されるデータには、ユーザーを特定できる情報は含まれないよう、匿名化または集計されます。

***

<a id="account-deletion-and-data-retention"></a>
# Account Deletion and Data Retention

## 1. Account Deletion Procedure

If you wish to delete your account and any associated data for this application, please follow the steps below.

### Deletion Request Method

To request account deletion, please contact the app developer (Jiro Takita) at the email address below with the following required information:

* **Recipient Email Address**: **`takijiro0925@gmail.com`**
* **Subject**: Account Deletion Request
* **Information to be included in the body**:
    1.  **Email Address associated with the account**: (Required)
    2.  **Current Nickname (Username)**: (Required)

Upon receiving your email, we will verify your identity and proceed with the deletion process. Please note that the procedure may take several days to complete.

---

## 2. Data Deletion and Retention Period

When an account deletion is requested, the following data will be deleted.

### Data to be Deleted

Once the account deletion is complete, the following data will be **permanently removed** from the application's database:

* **User Authentication Information**: (User ID, authentication email address managed by Firebase, etc.)
* **Nickname (Username)**
* **User-created Shopping List Data**: (List names, items, check status, etc.)

### Retained Data and Retention Period

For the purposes of legal compliance, fraud prevention, and maintaining app stability, some or all of the following data may be **retained for a specific period** even after account deletion.

| Data Type | Retention Period | Reason for Retention |
| :--- | :--- | :--- |
| **Crash Reports and Usage Logs** | Up to 90 days | For maintaining service quality and analyzing defects. Data is anonymized. |
| **Records related to Legal Compliance** | Period defined by law | For investigating misuse or fulfilling legal obligations. |

Any retained data will be anonymized or aggregated so that it cannot be used to identify the user.
