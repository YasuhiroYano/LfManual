###########################
概要
###########################

.. figure:: ../img/New0000.jpg
   :scale: 100
   :align: Right


「LoRaFactory」はprivate LoRa通信モジュール　ES920LR [1]_　を搭載したArduino Uno互換のIot基板です。
920MHz帯を使用したLoRa変調方式で条件の良い見通しのエリアでは、約30km以上の通信を可能とし、市街地エリアでも半径数kｍ程度のエリアをカバーします。
障害物の多い工場内でも十分な通信エリアを確保できます。 
LTE（携帯電話の通信）を使用する場合に比べて、自前でGatewayを設置する必要がありますが、通信費が不要で、多数の子機からデータを取集するのに適しています。
センサーとの接続に必要な回路は、市販されているAruduinoUno拡張基板(シールドと呼ばれる)に実装します。
GateWayとして同じLoRaFactoryを使用することができます。　USBでパソコン等に接続するのであれば、RoLaFactory基板だけでGateWayが作成できます。
WiFiまたはLANに対するGateWayを作成する場合は、シールドにWiFiモジュール等を搭載することで、実現できます。
これらのプログラムは `Arduino`_ IDEで作成することができます。　
通信モジュールの操作は、ライブラリとして提供されますので、簡単にIOTを始めることができます。
電源は制御装置でよく使用されるDC24Vに対応します。　また、頻繁に通信しなければ、単4電池2個で数年間の運用も可能です。

.. [1] ES920LRはEASELの商品です。: ES920LR_

.. _ES920LR: https://easel5.com/service/products-information/products/wireless-module/es920lr/
.. _Arduino: https://thinkit.co.jp/story/2013/02/12/3960