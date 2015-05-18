# Crash-Dump
PocketMine-MP Crash Dump Tue May 19 03:52:57 UTC 2015

Error: syntax error, unexpected 'class' (T_CLASS), expecting ',' or ';'
File: /TapRent/src/TapRent/Main
Line: 16
Type: E_PARSE

THIS CRASH WAS CAUSED BY A PLUGIN

Code:
[7] use pocketmine\math\Vector3 as Vector3;
[8] use pocketmine\level\Level;
[9] use pocketmine\command\Command;
[10] use pocketmine\command\CommandExecutor;
[11] use pocketmine\command\CommandSender;
[12] use pocketmine\event\Listener;
[13] use pocketmine\event\player\PlayerInteractEvent;
[14] use pocketmine\event\player\BlockBreakEvent
[15] 
[16] class Main extends PluginBase implements Listener, CommandExecutor {
[17] 
[18] public function onEnable(){
[19] 
[20] 	$this->saveDefaultConfig();
[21] 	$this->reloadConfig();
[22] 	$this->v = "1.0";
[23] 	$this->crt = "artide";
[24] 	$this->getLogger()->info("Plugin loaded successfully!");
[25] 	$this->getLogger()->info("version ".$this->v." by ".$this->crt);
[26] 	$this->getServer()->getPluginManager()->registerEvents($this, $this);

Backtrace:
#0 (): pocketmine\Server->crashDump()

PocketMine-MP version: 1.5dev #1146 [Protocol 26; API 1.12.0]
Git commit: 0000000000000000000000000000000000000000
uname -a: Linux localhost 3.0.31-787812 #1 SMP PREEMPT Tue Jun 4 00:57:38 KST 2013 armv7l
PHP Version: 5.6.2
Zend version: 2.6.0
OS : Linux, android

Loaded plugins:
EconomyAPI 2.0.7 by onebone for API(s) 1.0.0, 1.1.0, 1.2.0, 1.2.1, 1.3.0, 1.3.1, 1.4.0, 1.4.1
EconomyAuction 2.0.2 by onebone for API(s) 1.0.0, 1.1.0, 1.2.0, 1.2.1, 1.3.0, 1.3.1, 1.4.0, 1.4.1
EconomyCasino 2.0.1 by onebone for API(s) 1.0.0, 1.1.0, 1.2.0, 1.2.1, 1.3.0, 1.3.1, 1.4.0, 1.4.1
EconomyJob 2.0.3 by onebone for API(s) 1.0.0, 1.1.0, 1.2.0, 1.2.1, 1.3.0, 1.3.1, 1.4.0, 1.4.1
EconomyLand 2.0.7 by onebone for API(s) 1.12.0
EconomyProperty 2.0.4 by onebone for API(s) 1.12.0
EconomySell 2.0.5 by onebone for API(s) 1.12.0
EconomyShop 2.0.5 by onebone for API(s) 1.12.0
EconomyTax 2.0.2 by onebone for API(s) 1.0.0, 1.1.0, 1.2.0, 1.2.1, 1.3.0, 1.3.1, 1.4.0, 1.4.1
FastTransfer 1.0.1 by shoghicp for API(s) 1.12.0
SimpleWarp 1.4 by Falk for API(s) 1.0.0
TapToDo 2.1.2 by Falk for API(s) 1.0.0
FactionsPro 1.2.0 by Tethered_ for API(s) 1.4.0
ServerKits 1.3 by EvolSoft for API(s) 1.11.0
MassiveEconomy 1.0 R3 by EvolSoft for API(s) 1.9.0
PurePerms 1.1.1 by 64FF00 for API(s) 1.11.0
SimpleAuth 1.6.0 by PocketMine Team, shoghicp for API(s) 1.8.0
SimpleMessages 1.2 by Dutok for API(s) 1.0.0
ManyWorlds 1.3.4 by aliuly for API(s) 1.10.0
MCG76_WorldEdit 0.5.0 by minecraftgenius76 for API(s) 1.8.0
CustomChat INDEV by Array for API(s) 1.7.1
KillChat 1.0.1 by Array for API(s) 1.9.0
DevTools 1.10.0 by PocketMine Team for API(s) 1.3.1
SpawnMgr 1.1.0 by aliuly for API(s) 1.10.0
ClearLagg 1.1.0 by LegendOfMCPE for API(s) 1.0.0
essentialsTP 1.0.9 by  for API(s) 1.0.0
EconomyUsury 1.0.0 by onebone for API(s) 1.12.0
EconomyAirport 2.0.4 by onebone for API(s) 1.12.0
WorldProtect 1.2.4 by aliuly for API(s) 1.10.0
SimpleAuthHelper 1.2.1 by aliuly for API(s) 1.10.0
MassiveEconomyExample 1 by EvolSoft for API(s) 1.4.0

----------------------REPORT THE DATA BELOW THIS LINE-----------------------

===BEGIN CRASH DUMP===
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
KG9S/hpl5ReLo87vv/8vEjCrfQ==
===END CRASH DUMP===
