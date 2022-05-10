### *start load test:*

    sudo docker run --net host -v $(pwd):/var/loadtest -v $HOME/.ssh:/root/.ssh -it direvius/yandex-tank -c load.yaml ammo.txt
