# Changelog

# Changelog

## [1.310] - 2024-10-07

<table>
    <tr><td>lipic </td><td> MQTT - Přidáno resetování BCBOXU po odpojení Wi-Fi a GSM trvajícím déle než 10 minut </td></tr>
    <tr><td>lipic </td><td> MQTT - Přidáno zpracování příkazu, pro odpojení a vymazání seznamu wi-fi z DB </td></tr>
    <tr><td>lipic </td><td> MQTT - Zpracování příkazů pro povelní/zakázání wi-fi a gsm modemu </td></tr>
    <tr><td>lipic </td><td> GSM - přidáno zpracování response při publikování zprávy. Při poslání příkazu v okamžiku publikování, mohlo dojít k zahození příkazu </td></tr>
    <tr><td>lipic </td><td> MQTT - Oprava reportů </td></tr>
    <tr><td>lipic </td><td> MQTT - Snížen počet o znovu odeslání zprávy, dojde-li k chybě. V Hroznové se jinak posílaly reporty se starým časem.</td></tr>
</table>

## [1.300] - 2024-08-10

<table>
    <tr><td>lipic </td><td> GSM - přidáno zpracování response při publikování zprávy. Při poslání příkazu v okamžiku publikování, mohlo dojít k zahození příkazu </td></tr>
    <tr><td>lipic </td><td> GSM - úprava handlování gsm </td></tr>
    <tr><td>lipic </td><td> GSM - přidán MQTT RECONNECTING stav do reportů </td></tr>
    <tr><td>lipic </td><td> LOGOVÁNÍ - Přidáno ošetření pro maximální velikost logů, aby se nezaplnila paměťi </td></tr>
    <tr><td>lipic </td><td> GSM - Přidány podrobnější stavy gsm modemu </td></tr>
    <tr><td>lipic </td><td> GSM - Oprava znovu připojení po odpojení od operátora </td></tr>
    <tr><td>lipic </td><td> Wi-Fi - oprava posílání nenulové síly signálu při odpojené Wi-Fi </td></tr>
    <tr><td>lipic </td><td> GSM - posílání seznamu dostupných SSID, je-li BCBOX odpojen od Wi-Fi </td></tr>
    <tr><td>lipic </td><td> GSM - handlování změny wifi přes cloud </td></tr>
    <tr><td>lipic </td><td> CONFIG - přidáno povolení/zakázaní wi-fi </td></tr>
    <tr><td>lipic </td><td> BUGFIX - oprava konfigurace u captive portálu, docházelo k chybě při změně parametru </td></tr>
</table>

## [1.200] - 2024-07-02

<table>
    <tr><th>Author</th><th>Commit</th><th>Date</th></tr>
    <tr><td>lipic </td><td> GSM - oprava chyby u znovupřipojení.</td><td>2024-06-25</td></tr>
    <tr><td>lipic </td><td> MQTT - oprava reportování názvu AP.</td><td>2024-06-25</td></tr>
    <tr><td>lipic </td><td> GSM - přidáno logování chyb do souboru.</td><td>2024-06-25</td></tr>
    <tr><td>lipic </td><td> MQTT - přidáno logování chyb do souboru.</td><td>2024-06-24</td></tr>
    <tr><td>lipic </td><td> MQTT - úprava jádra mqtt handleru.</td><td>2024-06-24</td></tr>
    <tr><td>lipic </td><td> Wi-Fi - filtrování SSID, na základě síly signálu. Je-li menší než 50%, SSID se nebude reportovat na server (Nebude možnost se k němu připojit).</td><td>2024-06-05</td></tr>
    <tr><td>lipic </td><td> Wi-Fi - úprava přepočtu dBi na %.</td><td>2024-06-05</td></tr>
    <tr><td>lipic </td><td> MQTT - přidáno reportování názvu AP.</td><td>2024-06-04</td></tr>
    <tr><td>lipic </td><td> MQTT - přidáno reportování IP adresy.</td><td>2024-06-04</td></tr>
    <tr><td>lipic </td><td> GSM - oprava timeoutu u "MQTTCONNPARAM".</td><td>2024-06-03</td></tr>
    <tr><td>lipic </td><td> GSM - vyčítání IMEI sim karty.</td> <td>2024-05-11</td></tr>
</table>