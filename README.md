#### XX-Net-mini 4.5.1
Mini version of [XX-Net](https://github.com/XX-net/XX-Net).

Usage 
    
    pip3 install hpack hyper PySocks cryptography pyasn1 dnslib hyperframe -U
    pip3 -vvv install --upgrade --force-reinstall cffi
    
    git clone https://github.com/miketwes/XX-Net-mini.git
    cd XX-Net-mini/code/default/launcher/ && python3 start.py
    
    Please wait 1 or 2 seconds, till the terminal show:
        "Network is ok, you can start to surf the internet!"
    
    # Chromium

        chromium --proxy-server="http://127.0.0.1:8087"
    
    # Firefox 
    
        about:config
        network.proxy.type 1     
        network.proxy.http 127.0.0.1
        network.proxy.http_port 8087
   
    # Using your app id:
    
        put your appids in XX-Net-mini/data/config.json
    
        "gaeappids": [
            "yourappid1",
            "yourappid2"
        ],

    # To stop XX-Net-mini:
        press Ctrl + z on keyboard then at terminal run: pkill -9 python3
