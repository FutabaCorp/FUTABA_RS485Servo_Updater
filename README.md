# FUTABA_RS485Servo_Updater

本アプリケーションでは、RS485対応サーボ（BLA21-12R3-C01）のファームウェアアップデートを行うことが可能です。   
アプリケーションを使用する際は、このリポジトリをダウンロードして実行してください。  
アプリケーションの使用方法およびファームウェアアップデートの手順は以下のマニュアルをご確認ください。  
This application allows you to update the firmware of RS485 compatible servos (BLA21-12R3-C01).  
When using the application, download and run this repository.  
Please refer to the following manual for how to use the application and the firmware update procedure.  
<br>
[RS485サーボ_アップデートマニュアル.pdf](https://github.com/FutabaCorp/FUTABA_RS485Servo_Updater/blob/main/RS485%E3%82%B5%E3%83%BC%E3%83%9C_%E3%82%A2%E3%83%83%E3%83%97%E3%83%87%E3%83%BC%E3%83%88%E3%83%9E%E3%83%8B%E3%83%A5%E3%82%A2%E3%83%AB.pdf)
<br><br>

アップデートに使用するbinファイルは以下のフォルダに保存されています。  
アップデート対象の機種名が記載されたフォルダ内のbinファイルをご利用ください。  
The bin file used for the update is saved in the following folder.  
Please use the bin file in the folder containing the name of the model to be updated.  
<br>
[update_bin_files](https://github.com/FutabaCorp/FUTABA_RS485Servo_Updater/tree/main/update_bin_files)
<br><br>


### サーボファームウェアバージョン管理表（コマンド方式）

| Ver | 機種(期間) | 変更内容 |
| :---: | :--- | :--- |
| 101 | ・BLA21-12R3-C01 (2024/11\~2025/2) | ・新規ファームウェア |
| 103 | ・BLA21-12R3-C01 (2025/3\~) | ・UVLO機能が動作しない不具合を修正<br>・動作改善 |

### サーボファームウェアバージョン管理表（CM.BUS）

| Ver | 機種(期間) | 変更内容 |
| :---: | :--- | :--- |
| 2.00.0 | ・BLA21-12R3-C01 (2025/4\~) | ・新規ファームウェア |

### アプリケーションバージョン管理表

| Ver | 変更内容 |
| :---: | :--- |
| 1.2 | ・新規アプリケーション |

<br>

### Servo firmware version management table (Command Type)

| Ver | Model (Period) | Changes |
| :---: | :--- | :--- |
| 101 | ・BLA21-12R3-C01 (11/2024\~2/2025) | ・New Firmware. |
| 103 | ・BLA21-12R3-C01 (3/2025\~) | ・Fixed a bug that caused the UVLO function to not work.<br>・Improved operation. |

### Servo firmware version management table (CM.BUS)

| Ver | Model (Period) | Changes |
| :---: | :--- | :--- |
| 2.00.0 | ・BLA21-12R3-C01 (4/2025\~) | ・New Firmware. |

### Application version management table

| Ver | Changes |
| :---: | :--- |
| 1.2 | ・New applications |
