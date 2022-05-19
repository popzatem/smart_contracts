# Proxy
https://docs.openzeppelin.com/contracts/4.x/api/proxy
https://github.com/OpenZeppelin/openzeppelin-contracts/tree/v3.4.0/contracts/proxy

Core - ระบบหลัก
* Proxy
* UpgradeableProxy
* TransparentUpgradeableProxy
** Deploy
*** _LOGIC - Contract ที่ต้องการ Proxy
*** _ADMIN - Contract ProxyAdmin
*** _DATA - function ที่เรียกใน Contract {_LOGIC} แปลงเป็น hash (*เติม 0x) https://abi.hashex.org/


Utilities - ตัวจัดการ
* Initializable
* ProxyAdmin
** testnet : 0x84662dAa0b08e34297733A4266636fAA01ea8e8B