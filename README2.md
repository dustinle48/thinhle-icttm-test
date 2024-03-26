### 1. Start MinIO

```
docker-compose -f docker-compose.mino.yml up
```

### 2. Virtualenv

- Install virtualenv: https://www.javatpoint.com/install-virtualenv-ubuntu
- Create virtualenv

```
$ virtualenv --python=python3.8 venv
```

- Activate virtualenv

```
$ source ~/venv/bin/activate
```

- Tip
  You can use **fish** in ubuntu for better command line.

### 3. Docker

- Install docker if not existed: https://azdigi.com/blog/en/linux-server-en/tools-en/how-to-install-docker-on-ubuntu-22-04/
- Restart local machine if got error Access Denied

### 4. Note

- You may need to install **java-sdk** to use **PySpark**
- First run should be slow since we need to download packages.
