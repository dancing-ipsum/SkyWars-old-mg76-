# SkyWars-old-mg76-
Hi this plugun needs a update tried to fix it but cant plz try to this was made by mcg76

crash dump erro on 0.14.0

Genisys Crash Dump Sun Feb 21 14:32:46 UTC 2016

Error: Declaration of mcg76\skywars\map\SkyBlockGenerator::init(pocketmine\level\generator\GenerationChunkManager $level, pocketmine\utils\Random $random) must be compatible with pocketmine\level\generator\Generator::init(pocketmine\level\ChunkManager $level, pocketmine\utils\Random $random)
File: /Darkcraft_SkyWars_v1.0.4.phar/src/mcg76/skywars/map/SkyBlockGenerator
Line: 294
Type: E_COMPILE_ERROR

THIS CRASH WAS CAUSED BY A PLUGIN
此次出错由插件引起

Code:
[285] 		$this->random->setSeed ( 0xdeadbeef ^ ($chunkX << 8) ^ $chunkZ ^ $this->level->getSeed () );
[286] 		foreach ( $this->populators as $populator ) {
[287] 			$this->random->setSeed ( 0xdeadbeef ^ ($chunkX << 8) ^ $chunkZ ^ $this->level->getSeed () );
[288] 			$populator->populate ( $this->level, $chunkX, $chunkZ, $this->random );
[289] 		}
[290] 	}
[291] 	public function getSpawn() {
[292] 		return new Vector3 ( 132, 57, 129 );
[293] 	}
[294] }
[295] 
[296] 
[297] 
[298] 
[299] 
[300] 
[301] 
[302] 
[303] 
[304] 

Backtrace:
#0 (): pocketmine\Server->crashDump(boolean)

Genisys version: 1.1dev #0 [Protocol 45; API 2.0.0]
uname -a: Windows NT WIN-U79KH12MOJS 6.3 build 9600 (Windows Server 2012 R2 Datacenter Edition) i586
PHP version: 7.0.1
Zend version: 3.0.0
OS : WINNT, win

Loaded plugins:
加载的插件:
