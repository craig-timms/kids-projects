# Specs
The performance is based on battery voltage, motor, gears, and wheel size.
Spec'd out below the board has:
- 22.2V Lipo battery (6 cells in series or 6S)
- 190 KV motor
- 2.25:1 gear ratio (motor spins 2.25 times for every 1 time the wheel does)
- Top speed of 18 MPH

Top speed found using [ESK8 Calc](http://calc.esk8.it/#{%22batt-type-lipo%22:1,%22batt-cells%22:6,%22motor-kv%22:190,%22system-efficiency%22:85,%22motor-pulley-teeth%22:16,%22wheel-pulley-teeth%22:36,%22wheel-size%22:83}|) (current specs filled in)

# Parts

Name | Description | Link / Price
---- | ----------- | ------------
Controller | Makes battery juice motor juice | [$100](https://diyelectricskateboard.com/collections/featured-items/products/torque-esc-bldc-electronic-speed-controller)
Hardware Kit | Trucks/wheels/motor mount/gears+belt | [$200](https://diyelectricskateboard.com/collections/featured-items/products/single-motor-mechanical-kit)
Motor | Makes wheels spin - 190KV | [$90](https://diyelectricskateboard.com/collections/electric-skateboard-motors/products/electric-skateboard-motor-6355-190kv)
Battery | 3000mAh 6s 20C Lipo ([$43/4Ah](https://hobbyking.com/en_us/turnigy-4000mah-6s-30c-lipo-pack-w-xt90.html)-[$46/5Ah](https://hobbyking.com/en_us/turnigy-5000mah-6s-20c-lipo-pack-w-xt-90.html)) | [$30](https://hobbyking.com/en_us/zippy-compact-3000mah-6s-20c-lipo-pack-w-xt60u-connector.html)
Remote | Wireless PS2 Controller | [$24](https://www.robotshop.com/en/lynxmotion-ps2-controller-v4.html)
Arduino Nano | Microcontroller to talk to remote | [$8](https://www.amazon.com/Arduino-Board-ATmega328P-Micro-Controller-Projects/dp/B07X5VQ9XH/ref=sr_1_11_sspa?keywords=arduino+nano&qid=1575646075&sr=8-11-spons&psc=1&spLa=ZW5jcnlwdGVkUXVhbGlmaWVyPUExNTgzMFAxSVU5S1lWJmVuY3J5cHRlZElkPUEwMzY5MTkyVkVST0dGM1NPQVVVJmVuY3J5cHRlZEFkSWQ9QTA2MzczMzQ1T0hQN1Y4TVFHTlomd2lkZ2V0TmFtZT1zcF9tdGYmYWN0aW9uPWNsaWNrUmVkaXJlY3QmZG9Ob3RMb2dDbGljaz10cnVl)
Breaker | To turn off battery - 50A | [$17](https://www.amazon.com/ZOOKOTO-12V-32V-Circuit-Inverter-Waterproof/dp/B07FLRCY7L/ref=pd_cp_263_4/141-2204688-8465921?_encoding=UTF8&pd_rd_i=B07FLRCY7L&pd_rd_r=ff0dce23-6e1a-45f3-89d8-013c39715f78&pd_rd_w=vGlY9&pd_rd_wg=KhAO1&pf_rd_p=0e5324e1-c848-4872-bbd5-5be6baedf80e&pf_rd_r=638KBZS9X2FMS90YYRQ6&psc=1&refRID=638KBZS9X2FMS90YYRQ6)
Deck | With tape | [$47](https://www.skateshred.com/wholesale-bamboo-drop-through-deck.html?gclid=Cj0KCQiA89zvBRDoARIsAOIePbA2B2-PNJZpeLQgEcEMo-dqfsFkEo4hk-PpT3CMhM_6dFGui_e2UiwaAnApEALw_wcB) / [$45](https://www.skateshred.com/wholesale-blank-longboard-decks/40-x-9-75-kicktail-blank-deck-bamboo-longboard.html?gclid=Cj0KCQiA89zvBRDoARIsAOIePbDN57xqr5zFoAinX_8BMAjye9ErD7CR2YDVtCbnUANsdvXCyiXSKTAaAjYSEALw_wcB)
