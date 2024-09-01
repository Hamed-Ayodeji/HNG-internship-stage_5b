# /var/log/stage_5b/out.log

```shell
ubuntu@ip-10-0-0-5:~$ sudo cat /var/log/stage_5b/out.log
   $6$Qn4DcxfEuPQoD4Tp$ULEXnLJQKisfGqoX669I9yo/jRUAJ8eFtojUaWV3xu.QFWcD3/GeSczF41NvCjW0DGOSixWd5.4PBGcCXLXfn/
   Reading package lists...
   Building dependency tree...
   Reading state information...
   The following additional packages will be installed:
   python3-pip-whl python3-setuptools-whl python3.10-venv
   The following NEW packages will be installed:
   python3-pip-whl python3-setuptools-whl python3-venv python3.10-venv
   0 upgraded, 4 newly installed, 0 to remove and 9 not upgraded.
   Need to get 2474 kB of archives.
   After this operation, 2890 kB of additional disk space will be used.
   Get:1 http://us-east-1.ec2.archive.ubuntu.com/ubuntu jammy-updates/universe amd64 python3-pip-whl all 22.0.2+dfsg-1ubuntu0.4 [1680 kB]
   Get:2 http://us-east-1.ec2.archive.ubuntu.com/ubuntu jammy-updates/universe amd64 python3-setuptools-whl all 59.6.0-1.2ubuntu0.22.04.1 [788 kB]
   Get:3 http://us-east-1.ec2.archive.ubuntu.com/ubuntu jammy-updates/universe amd64 python3.10-venv amd64 3.10.12-1~22.04.4 [5712 B]
   Get:4 http://us-east-1.ec2.archive.ubuntu.com/ubuntu jammy-updates/universe amd64 python3-venv amd64 3.10.6-1~22.04 [1038 B]
   Fetched 2474 kB in 0s (32.9 MB/s)
   Selecting previously unselected package python3-pip-whl.
   (Reading database ... 65331 files and directories currently installed.)
   Preparing to unpack .../python3-pip-whl_22.0.2+dfsg-1ubuntu0.4_all.deb ...
   Unpacking python3-pip-whl (22.0.2+dfsg-1ubuntu0.4) ...
   Selecting previously unselected package python3-setuptools-whl.
   Preparing to unpack .../python3-setuptools-whl_59.6.0-1.2ubuntu0.22.04.1_all.deb ...
   Unpacking python3-setuptools-whl (59.6.0-1.2ubuntu0.22.04.1) ...
   Selecting previously unselected package python3.10-venv.
   Preparing to unpack .../python3.10-venv_3.10.12-1~22.04.4_amd64.deb ...
   Unpacking python3.10-venv (3.10.12-1~22.04.4) ...
   Selecting previously unselected package python3-venv.
   Preparing to unpack .../python3-venv_3.10.6-1~22.04_amd64.deb ...
   Unpacking python3-venv (3.10.6-1~22.04) ...
   Setting up python3-setuptools-whl (59.6.0-1.2ubuntu0.22.04.1) ...
   Setting up python3-pip-whl (22.0.2+dfsg-1ubuntu0.4) ...
   Setting up python3.10-venv (3.10.12-1~22.04.4) ...
   Setting up python3-venv (3.10.6-1~22.04) ...
   NEEDRESTART-VER: 3.5
   NEEDRESTART-KCUR: 6.5.0-1023-aws
   NEEDRESTART-KEXP: 6.5.0-1023-aws
   NEEDRESTART-KSTA: 1

   Reading package lists...
   Building dependency tree...
   Reading state information...
   The following additional packages will be installed:
   libpq5
   Suggested packages:
   python-psycopg2-doc
   The following NEW packages will be installed:
   libpq5 python3-psycopg2
   0 upgraded, 2 newly installed, 0 to remove and 9 not upgraded.
   Need to get 285 kB of archives.
   After this operation, 913 kB of additional disk space will be used.
   Get:1 http://us-east-1.ec2.archive.ubuntu.com/ubuntu jammy-updates/main amd64 libpq5 amd64 14.12-0ubuntu0.22.04.1 [149 kB]
   Get:2 http://us-east-1.ec2.archive.ubuntu.com/ubuntu jammy/main amd64 python3-psycopg2 amd64 2.9.2-1build2 [136 kB]
   Fetched 285 kB in 0s (9626 kB/s)
   Selecting previously unselected package libpq5:amd64.
   (Reading database ... 65347 files and directories currently installed.)
   Preparing to unpack .../libpq5_14.12-0ubuntu0.22.04.1_amd64.deb ...
   Unpacking libpq5:amd64 (14.12-0ubuntu0.22.04.1) ...
   Selecting previously unselected package python3-psycopg2.
   Preparing to unpack .../python3-psycopg2_2.9.2-1build2_amd64.deb ...
   Unpacking python3-psycopg2 (2.9.2-1build2) ...
   Setting up libpq5:amd64 (14.12-0ubuntu0.22.04.1) ...
   Setting up python3-psycopg2 (2.9.2-1build2) ...
   Processing triggers for libc-bin (2.35-0ubuntu3.8) ...
   NEEDRESTART-VER: 3.5
   NEEDRESTART-KCUR: 6.5.0-1023-aws
   NEEDRESTART-KEXP: 6.5.0-1023-aws
   NEEDRESTART-KSTA: 1

   No output captured for git_output

   /opt/stage_5b/venv
   Collecting alembic==1.13.2
   Downloading alembic-1.13.2-py3-none-any.whl (232 kB)
      ━━━━━━━━━━━━━━━━━━━━━━━━━━━━━━━━━━━━━━━ 233.0/233.0 KB 5.0 MB/s eta 0:00:00
   Collecting annotated-types==0.7.0
   Downloading annotated_types-0.7.0-py3-none-any.whl (13 kB)
   Collecting anyio==4.4.0
   Downloading anyio-4.4.0-py3-none-any.whl (86 kB)
      ━━━━━━━━━━━━━━━━━━━━━━━━━━━━━━━━━━━━━━━━ 86.8/86.8 KB 15.8 MB/s eta 0:00:00
   Collecting Authlib==1.3.1
   Downloading Authlib-1.3.1-py2.py3-none-any.whl (223 kB)
      ━━━━━━━━━━━━━━━━━━━━━━━━━━━━━━━━━━━━━━ 223.8/223.8 KB 32.4 MB/s eta 0:00:00
   Collecting bcrypt==4.1.3
   Downloading bcrypt-4.1.3-cp39-abi3-manylinux_2_28_x86_64.whl (283 kB)
      ━━━━━━━━━━━━━━━━━━━━━━━━━━━━━━━━━━━━━━ 283.7/283.7 KB 38.7 MB/s eta 0:00:00
   Collecting certifi==2024.7.4
   Downloading certifi-2024.7.4-py3-none-any.whl (162 kB)
      ━━━━━━━━━━━━━━━━━━━━━━━━━━━━━━━━━━━━━━ 163.0/163.0 KB 23.3 MB/s eta 0:00:00
   Collecting cffi==1.16.0
   Downloading cffi-1.16.0-cp310-cp310-manylinux_2_17_x86_64.manylinux2014_x86_64.whl (443 kB)
      ━━━━━━━━━━━━━━━━━━━━━━━━━━━━━━━━━━━━━━ 443.9/443.9 KB 48.3 MB/s eta 0:00:00
   Collecting charset-normalizer==3.3.2
   Downloading charset_normalizer-3.3.2-cp310-cp310-manylinux_2_17_x86_64.manylinux2014_x86_64.whl (142 kB)
      ━━━━━━━━━━━━━━━━━━━━━━━━━━━━━━━━━━━━━━ 142.1/142.1 KB 26.0 MB/s eta 0:00:00
   Collecting click==8.1.7
   Downloading click-8.1.7-py3-none-any.whl (97 kB)
      ━━━━━━━━━━━━━━━━━━━━━━━━━━━━━━━━━━━━━━━━ 97.9/97.9 KB 16.5 MB/s eta 0:00:00
   Collecting cryptography==43.0.0
   Downloading cryptography-43.0.0-cp39-abi3-manylinux_2_28_x86_64.whl (4.0 MB)
      ━━━━━━━━━━━━━━━━━━━━━━━━━━━━━━━━━━━━━━━━ 4.0/4.0 MB 71.5 MB/s eta 0:00:00
   Collecting dnspython==2.6.1
   Downloading dnspython-2.6.1-py3-none-any.whl (307 kB)
      ━━━━━━━━━━━━━━━━━━━━━━━━━━━━━━━━━━━━━━ 307.7/307.7 KB 22.9 MB/s eta 0:00:00
   Collecting ecdsa==0.19.0
   Downloading ecdsa-0.19.0-py2.py3-none-any.whl (149 kB)
      ━━━━━━━━━━━━━━━━━━━━━━━━━━━━━━━━━━━━━━ 149.3/149.3 KB 22.6 MB/s eta 0:00:00
   Collecting email_validator==2.2.0
   Downloading email_validator-2.2.0-py3-none-any.whl (33 kB)
   Collecting exceptiongroup==1.2.2
   Downloading exceptiongroup-1.2.2-py3-none-any.whl (16 kB)
   Collecting fastapi==0.111.1
   Downloading fastapi-0.111.1-py3-none-any.whl (92 kB)
      ━━━━━━━━━━━━━━━━━━━━━━━━━━━━━━━━━━━━━━━━ 92.2/92.2 KB 16.9 MB/s eta 0:00:00
   Collecting fastapi-cli==0.0.4
   Downloading fastapi_cli-0.0.4-py3-none-any.whl (9.5 kB)
   Collecting greenlet==3.0.3
   Downloading greenlet-3.0.3-cp310-cp310-manylinux_2_24_x86_64.manylinux_2_28_x86_64.whl (616 kB)
      ━━━━━━━━━━━━━━━━━━━━━━━━━━━━━━━━━━━━━━ 616.0/616.0 KB 56.7 MB/s eta 0:00:00
   Collecting h11==0.14.0
   Downloading h11-0.14.0-py3-none-any.whl (58 kB)
      ━━━━━━━━━━━━━━━━━━━━━━━━━━━━━━━━━━━━━━━━ 58.3/58.3 KB 11.2 MB/s eta 0:00:00
   Collecting httpcore==1.0.5
   Downloading httpcore-1.0.5-py3-none-any.whl (77 kB)
      ━━━━━━━━━━━━━━━━━━━━━━━━━━━━━━━━━━━━━━━━ 77.9/77.9 KB 14.9 MB/s eta 0:00:00
   Collecting httptools==0.6.1
   Downloading httptools-0.6.1-cp310-cp310-manylinux_2_5_x86_64.manylinux1_x86_64.manylinux_2_17_x86_64.manylinux2014_x86_64.whl (341 kB)
      ━━━━━━━━━━━━━━━━━━━━━━━━━━━━━━━━━━━━━━ 341.4/341.4 KB 41.6 MB/s eta 0:00:00
   Collecting httpx==0.27.0
   Downloading httpx-0.27.0-py3-none-any.whl (75 kB)
      ━━━━━━━━━━━━━━━━━━━━━━━━━━━━━━━━━━━━━━━━ 75.6/75.6 KB 13.6 MB/s eta 0:00:00
   Collecting idna==3.7
   Downloading idna-3.7-py3-none-any.whl (66 kB)
      ━━━━━━━━━━━━━━━━━━━━━━━━━━━━━━━━━━━━━━━━ 66.8/66.8 KB 12.9 MB/s eta 0:00:00
   Collecting iniconfig==2.0.0
   Downloading iniconfig-2.0.0-py3-none-any.whl (5.9 kB)
   Collecting itsdangerous==2.2.0
   Downloading itsdangerous-2.2.0-py3-none-any.whl (16 kB)
   Collecting Jinja2==3.1.4
   Downloading jinja2-3.1.4-py3-none-any.whl (133 kB)
      ━━━━━━━━━━━━━━━━━━━━━━━━━━━━━━━━━━━━━━ 133.3/133.3 KB 22.2 MB/s eta 0:00:00
   Collecting Mako==1.3.5
   Downloading Mako-1.3.5-py3-none-any.whl (78 kB)
      ━━━━━━━━━━━━━━━━━━━━━━━━━━━━━━━━━━━━━━━━ 78.6/78.6 KB 15.0 MB/s eta 0:00:00
   Collecting markdown-it-py==3.0.0
   Downloading markdown_it_py-3.0.0-py3-none-any.whl (87 kB)
      ━━━━━━━━━━━━━━━━━━━━━━━━━━━━━━━━━━━━━━━━ 87.5/87.5 KB 15.8 MB/s eta 0:00:00
   Collecting MarkupSafe==2.1.5
   Downloading MarkupSafe-2.1.5-cp310-cp310-manylinux_2_17_x86_64.manylinux2014_x86_64.whl (25 kB)
   Collecting mdurl==0.1.2
   Downloading mdurl-0.1.2-py3-none-any.whl (10.0 kB)
   Collecting packaging==24.1
   Downloading packaging-24.1-py3-none-any.whl (53 kB)
      ━━━━━━━━━━━━━━━━━━━━━━━━━━━━━━━━━━━━━━━━ 54.0/54.0 KB 10.1 MB/s eta 0:00:00
   Collecting passlib==1.7.4
   Downloading passlib-1.7.4-py2.py3-none-any.whl (525 kB)
      ━━━━━━━━━━━━━━━━━━━━━━━━━━━━━━━━━━━━━━ 525.6/525.6 KB 51.3 MB/s eta 0:00:00
   Collecting pluggy==1.5.0
   Downloading pluggy-1.5.0-py3-none-any.whl (20 kB)
   Collecting psycopg2-binary==2.9.9
   Downloading psycopg2_binary-2.9.9-cp310-cp310-manylinux_2_17_x86_64.manylinux2014_x86_64.whl (3.0 MB)
      ━━━━━━━━━━━━━━━━━━━━━━━━━━━━━━━━━━━━━━━━ 3.0/3.0 MB 76.7 MB/s eta 0:00:00
   Collecting pyasn1==0.6.0
   Downloading pyasn1-0.6.0-py2.py3-none-any.whl (85 kB)
      ━━━━━━━━━━━━━━━━━━━━━━━━━━━━━━━━━━━━━━━━ 85.3/85.3 KB 16.0 MB/s eta 0:00:00
   Collecting pycparser==2.22
   Downloading pycparser-2.22-py3-none-any.whl (117 kB)
      ━━━━━━━━━━━━━━━━━━━━━━━━━━━━━━━━━━━━━━ 117.6/117.6 KB 21.2 MB/s eta 0:00:00
   Collecting pydantic==2.8.2
   Downloading pydantic-2.8.2-py3-none-any.whl (423 kB)
      ━━━━━━━━━━━━━━━━━━━━━━━━━━━━━━━━━━━━━━ 423.9/423.9 KB 47.4 MB/s eta 0:00:00
   Collecting pydantic-settings==2.3.4
   Downloading pydantic_settings-2.3.4-py3-none-any.whl (22 kB)
   Collecting pydantic_core==2.20.1
   Downloading pydantic_core-2.20.1-cp310-cp310-manylinux_2_17_x86_64.manylinux2014_x86_64.whl (2.1 MB)
      ━━━━━━━━━━━━━━━━━━━━━━━━━━━━━━━━━━━━━━━━ 2.1/2.1 MB 87.4 MB/s eta 0:00:00
   Collecting Pygments==2.18.0
   Downloading pygments-2.18.0-py3-none-any.whl (1.2 MB)
      ━━━━━━━━━━━━━━━━━━━━━━━━━━━━━━━━━━━━━━━━ 1.2/1.2 MB 73.2 MB/s eta 0:00:00
   Collecting PyJWT==2.8.0
   Downloading PyJWT-2.8.0-py3-none-any.whl (22 kB)
   Collecting PyMySQL==1.1.1
   Downloading PyMySQL-1.1.1-py3-none-any.whl (44 kB)
      ━━━━━━━━━━━━━━━━━━━━━━━━━━━━━━━━━━━━━━━━ 45.0/45.0 KB 8.1 MB/s eta 0:00:00
   Collecting pytest==8.2.2
   Downloading pytest-8.2.2-py3-none-any.whl (339 kB)
      ━━━━━━━━━━━━━━━━━━━━━━━━━━━━━━━━━━━━━━ 339.9/339.9 KB 38.6 MB/s eta 0:00:00
   Collecting pytest-asyncio==0.23.8
   Downloading pytest_asyncio-0.23.8-py3-none-any.whl (17 kB)
   Collecting pytest-mock==3.14.0
   Downloading pytest_mock-3.14.0-py3-none-any.whl (9.9 kB)
   Collecting python-decouple==3.8
   Downloading python_decouple-3.8-py3-none-any.whl (9.9 kB)
   Collecting python-dotenv==1.0.1
   Downloading python_dotenv-1.0.1-py3-none-any.whl (19 kB)
   Collecting python-jose==3.3.0
   Downloading python_jose-3.3.0-py2.py3-none-any.whl (33 kB)
   Collecting python-multipart==0.0.9
   Downloading python_multipart-0.0.9-py3-none-any.whl (22 kB)
   Collecting PyYAML==6.0.1
   Downloading PyYAML-6.0.1-cp310-cp310-manylinux_2_17_x86_64.manylinux2014_x86_64.whl (705 kB)
      ━━━━━━━━━━━━━━━━━━━━━━━━━━━━━━━━━━━━━━ 705.5/705.5 KB 62.7 MB/s eta 0:00:00
   Collecting requests==2.32.3
   Downloading requests-2.32.3-py3-none-any.whl (64 kB)
      ━━━━━━━━━━━━━━━━━━━━━━━━━━━━━━━━━━━━━━━━ 64.9/64.9 KB 12.3 MB/s eta 0:00:00
   Collecting rich==13.7.1
   Downloading rich-13.7.1-py3-none-any.whl (240 kB)
      ━━━━━━━━━━━━━━━━━━━━━━━━━━━━━━━━━━━━━━ 240.7/240.7 KB 22.9 MB/s eta 0:00:00
   Collecting rsa==4.9
   Downloading rsa-4.9-py3-none-any.whl (34 kB)
   Collecting shellingham==1.5.4
   Downloading shellingham-1.5.4-py2.py3-none-any.whl (9.8 kB)
   Collecting six==1.16.0
   Downloading six-1.16.0-py2.py3-none-any.whl (11 kB)
   Collecting sniffio==1.3.1
   Downloading sniffio-1.3.1-py3-none-any.whl (10 kB)
   Collecting SQLAlchemy==2.0.31
   Downloading SQLAlchemy-2.0.31-cp310-cp310-manylinux_2_17_x86_64.manylinux2014_x86_64.whl (3.1 MB)
      ━━━━━━━━━━━━━━━━━━━━━━━━━━━━━━━━━━━━━━━━ 3.1/3.1 MB 80.0 MB/s eta 0:00:00
   Collecting starlette==0.37.2
   Downloading starlette-0.37.2-py3-none-any.whl (71 kB)
      ━━━━━━━━━━━━━━━━━━━━━━━━━━━━━━━━━━━━━━━━ 71.9/71.9 KB 13.1 MB/s eta 0:00:00
   Collecting tomli==2.0.1
   Downloading tomli-2.0.1-py3-none-any.whl (12 kB)
   Collecting typer==0.12.3
   Downloading typer-0.12.3-py3-none-any.whl (47 kB)
      ━━━━━━━━━━━━━━━━━━━━━━━━━━━━━━━━━━━━━━━━ 47.2/47.2 KB 9.1 MB/s eta 0:00:00
   Collecting typing_extensions==4.12.2
   Downloading typing_extensions-4.12.2-py3-none-any.whl (37 kB)
   Collecting urllib3==2.2.2
   Downloading urllib3-2.2.2-py3-none-any.whl (121 kB)
      ━━━━━━━━━━━━━━━━━━━━━━━━━━━━━━━━━━━━━━ 121.4/121.4 KB 19.9 MB/s eta 0:00:00
   Collecting uuid7==0.1.0
   Downloading uuid7-0.1.0-py2.py3-none-any.whl (7.5 kB)
   Collecting uvicorn==0.30.3
   Downloading uvicorn-0.30.3-py3-none-any.whl (62 kB)
      ━━━━━━━━━━━━━━━━━━━━━━━━━━━━━━━━━━━━━━━━ 62.8/62.8 KB 6.7 MB/s eta 0:00:00
   Collecting uvloop==0.19.0
   Downloading uvloop-0.19.0-cp310-cp310-manylinux_2_17_x86_64.manylinux2014_x86_64.whl (3.4 MB)
      ━━━━━━━━━━━━━━━━━━━━━━━━━━━━━━━━━━━━━━━━ 3.4/3.4 MB 81.2 MB/s eta 0:00:00
   Collecting watchfiles==0.22.0
   Downloading watchfiles-0.22.0-cp310-cp310-manylinux_2_17_x86_64.manylinux2014_x86_64.whl (1.2 MB)
      ━━━━━━━━━━━━━━━━━━━━━━━━━━━━━━━━━━━━━━━━ 1.2/1.2 MB 70.4 MB/s eta 0:00:00
   Collecting websockets==12.0
   Downloading websockets-12.0-cp310-cp310-manylinux_2_5_x86_64.manylinux1_x86_64.manylinux_2_17_x86_64.manylinux2014_x86_64.whl (130 kB)
      ━━━━━━━━━━━━━━━━━━━━━━━━━━━━━━━━━━━━━━ 130.2/130.2 KB 23.1 MB/s eta 0:00:00
   Collecting pytz==2024.1
   Downloading pytz-2024.1-py2.py3-none-any.whl (505 kB)
      ━━━━━━━━━━━━━━━━━━━━━━━━━━━━━━━━━━━━━━ 505.5/505.5 KB 51.9 MB/s eta 0:00:00
   Installing collected packages: pytz, python-decouple, passlib, websockets, uvloop, uuid7, urllib3, typing_extensions, tomli, sniffio, six, shellingham, PyYAML, python-multipart, python-dotenv, PyMySQL, PyJWT, Pygments, pycparser, pyasn1, psycopg2-binary, pluggy, packaging, mdurl, MarkupSafe, itsdangerous, iniconfig, idna, httptools, h11, greenlet, exceptiongroup, dnspython, click, charset-normalizer, certifi, bcrypt, annotated-types, uvicorn, SQLAlchemy, rsa, requests, pytest, pydantic_core, markdown-it-py, Mako, Jinja2, httpcore, email_validator, ecdsa, cffi, anyio, watchfiles, starlette, rich, python-jose, pytest-mock, pytest-asyncio, pydantic, httpx, cryptography, alembic, typer, pydantic-settings, Authlib, fastapi-cli, fastapi
   Successfully installed Authlib-1.3.1 Jinja2-3.1.4 Mako-1.3.5 MarkupSafe-2.1.5 PyJWT-2.8.0 PyMySQL-1.1.1 PyYAML-6.0.1 Pygments-2.18.0 SQLAlchemy-2.0.31 alembic-1.13.2 annotated-types-0.7.0 anyio-4.4.0 bcrypt-4.1.3 certifi-2024.7.4 cffi-1.16.0 charset-normalizer-3.3.2 click-8.1.7 cryptography-43.0.0 dnspython-2.6.1 ecdsa-0.19.0 email_validator-2.2.0 exceptiongroup-1.2.2 fastapi-0.111.1 fastapi-cli-0.0.4 greenlet-3.0.3 h11-0.14.0 httpcore-1.0.5 httptools-0.6.1 httpx-0.27.0 idna-3.7 iniconfig-2.0.0 itsdangerous-2.2.0 markdown-it-py-3.0.0 mdurl-0.1.2 packaging-24.1 passlib-1.7.4 pluggy-1.5.0 psycopg2-binary-2.9.9 pyasn1-0.6.0 pycparser-2.22 pydantic-2.8.2 pydantic-settings-2.3.4 pydantic_core-2.20.1 pytest-8.2.2 pytest-asyncio-0.23.8 pytest-mock-3.14.0 python-decouple-3.8 python-dotenv-1.0.1 python-jose-3.3.0 python-multipart-0.0.9 pytz-2024.1 requests-2.32.3 rich-13.7.1 rsa-4.9 shellingham-1.5.4 six-1.16.0 sniffio-1.3.1 starlette-0.37.2 tomli-2.0.1 typer-0.12.3 typing_extensions-4.12.2 urllib3-2.2.2 uuid7-0.1.0 uvicorn-0.30.3 uvloop-0.19.0 watchfiles-0.22.0 websockets-12.0

   Reading package lists...
   Building dependency tree...
   Reading state information...
   The following additional packages will be installed:
   libcommon-sense-perl libjson-perl libjson-xs-perl libllvm14
   libsensors-config libsensors5 libtypes-serialiser-perl postgresql-14
   postgresql-client-14 postgresql-client-common postgresql-common ssl-cert
   sysstat
   Suggested packages:
   lm-sensors postgresql-doc postgresql-doc-14 isag
   The following NEW packages will be installed:
   libcommon-sense-perl libjson-perl libjson-xs-perl libllvm14
   libsensors-config libsensors5 libtypes-serialiser-perl postgresql
   postgresql-14 postgresql-client-14 postgresql-client-common
   postgresql-common ssl-cert sysstat
   0 upgraded, 14 newly installed, 0 to remove and 9 not upgraded.
   Need to get 42.3 MB of archives.
   After this operation, 161 MB of additional disk space will be used.
   Get:1 http://us-east-1.ec2.archive.ubuntu.com/ubuntu jammy/main amd64 libcommon-sense-perl amd64 3.75-2build1 [21.1 kB]
   Get:2 http://us-east-1.ec2.archive.ubuntu.com/ubuntu jammy/main amd64 libjson-perl all 4.04000-1 [81.8 kB]
   Get:3 http://us-east-1.ec2.archive.ubuntu.com/ubuntu jammy/main amd64 libtypes-serialiser-perl all 1.01-1 [11.6 kB]
   Get:4 http://us-east-1.ec2.archive.ubuntu.com/ubuntu jammy/main amd64 libjson-xs-perl amd64 4.030-1build3 [87.2 kB]
   Get:5 http://us-east-1.ec2.archive.ubuntu.com/ubuntu jammy-updates/main amd64 libllvm14 amd64 1:14.0.0-1ubuntu1.1 [24.0 MB]
   Get:6 http://us-east-1.ec2.archive.ubuntu.com/ubuntu jammy/main amd64 libsensors-config all 1:3.6.0-7ubuntu1 [5274 B]
   Get:7 http://us-east-1.ec2.archive.ubuntu.com/ubuntu jammy/main amd64 libsensors5 amd64 1:3.6.0-7ubuntu1 [26.3 kB]
   Get:8 http://us-east-1.ec2.archive.ubuntu.com/ubuntu jammy/main amd64 postgresql-client-common all 238 [29.6 kB]
   Get:9 http://us-east-1.ec2.archive.ubuntu.com/ubuntu jammy-updates/main amd64 postgresql-client-14 amd64 14.12-0ubuntu0.22.04.1 [1223 kB]
   Get:10 http://us-east-1.ec2.archive.ubuntu.com/ubuntu jammy/main amd64 ssl-cert all 1.1.2 [17.4 kB]
   Get:11 http://us-east-1.ec2.archive.ubuntu.com/ubuntu jammy/main amd64 postgresql-common all 238 [169 kB]
   Get:12 http://us-east-1.ec2.archive.ubuntu.com/ubuntu jammy-updates/main amd64 postgresql-14 amd64 14.12-0ubuntu0.22.04.1 [16.2 MB]
   Get:13 http://us-east-1.ec2.archive.ubuntu.com/ubuntu jammy/main amd64 postgresql all 14+238 [3288 B]
   Get:14 http://us-east-1.ec2.archive.ubuntu.com/ubuntu jammy-updates/main amd64 sysstat amd64 12.5.2-2ubuntu0.2 [487 kB]
   Preconfiguring packages ...
   Fetched 42.3 MB in 1s (64.6 MB/s)
   Selecting previously unselected package libcommon-sense-perl:amd64.
   (Reading database ... 65372 files and directories currently installed.)
   Preparing to unpack .../00-libcommon-sense-perl_3.75-2build1_amd64.deb ...
   Unpacking libcommon-sense-perl:amd64 (3.75-2build1) ...
   Selecting previously unselected package libjson-perl.
   Preparing to unpack .../01-libjson-perl_4.04000-1_all.deb ...
   Unpacking libjson-perl (4.04000-1) ...
   Selecting previously unselected package libtypes-serialiser-perl.
   Preparing to unpack .../02-libtypes-serialiser-perl_1.01-1_all.deb ...
   Unpacking libtypes-serialiser-perl (1.01-1) ...
   Selecting previously unselected package libjson-xs-perl.
   Preparing to unpack .../03-libjson-xs-perl_4.030-1build3_amd64.deb ...
   Unpacking libjson-xs-perl (4.030-1build3) ...
   Selecting previously unselected package libllvm14:amd64.
   Preparing to unpack .../04-libllvm14_1%3a14.0.0-1ubuntu1.1_amd64.deb ...
   Unpacking libllvm14:amd64 (1:14.0.0-1ubuntu1.1) ...
   Selecting previously unselected package libsensors-config.
   Preparing to unpack .../05-libsensors-config_1%3a3.6.0-7ubuntu1_all.deb ...
   Unpacking libsensors-config (1:3.6.0-7ubuntu1) ...
   Selecting previously unselected package libsensors5:amd64.
   Preparing to unpack .../06-libsensors5_1%3a3.6.0-7ubuntu1_amd64.deb ...
   Unpacking libsensors5:amd64 (1:3.6.0-7ubuntu1) ...
   Selecting previously unselected package postgresql-client-common.
   Preparing to unpack .../07-postgresql-client-common_238_all.deb ...
   Unpacking postgresql-client-common (238) ...
   Selecting previously unselected package postgresql-client-14.
   Preparing to unpack .../08-postgresql-client-14_14.12-0ubuntu0.22.04.1_amd64.deb ...
   Unpacking postgresql-client-14 (14.12-0ubuntu0.22.04.1) ...
   Selecting previously unselected package ssl-cert.
   Preparing to unpack .../09-ssl-cert_1.1.2_all.deb ...
   Unpacking ssl-cert (1.1.2) ...
   Selecting previously unselected package postgresql-common.
   Preparing to unpack .../10-postgresql-common_238_all.deb ...
   Adding 'diversion of /usr/bin/pg_config to /usr/bin/pg_config.libpq-dev by postgresql-common'
   Unpacking postgresql-common (238) ...
   Selecting previously unselected package postgresql-14.
   Preparing to unpack .../11-postgresql-14_14.12-0ubuntu0.22.04.1_amd64.deb ...
   Unpacking postgresql-14 (14.12-0ubuntu0.22.04.1) ...
   Selecting previously unselected package postgresql.
   Preparing to unpack .../12-postgresql_14+238_all.deb ...
   Unpacking postgresql (14+238) ...
   Selecting previously unselected package sysstat.
   Preparing to unpack .../13-sysstat_12.5.2-2ubuntu0.2_amd64.deb ...
   Unpacking sysstat (12.5.2-2ubuntu0.2) ...
   Setting up postgresql-client-common (238) ...
   Setting up libsensors-config (1:3.6.0-7ubuntu1) ...
   Setting up libcommon-sense-perl:amd64 (3.75-2build1) ...
   Setting up postgresql-client-14 (14.12-0ubuntu0.22.04.1) ...
   update-alternatives: using /usr/share/postgresql/14/man/man1/psql.1.gz to provide /usr/share/man/man1/psql.1.gz (psql.1.gz) in auto mode
   Setting up ssl-cert (1.1.2) ...
   Setting up libsensors5:amd64 (1:3.6.0-7ubuntu1) ...
   Setting up libllvm14:amd64 (1:14.0.0-1ubuntu1.1) ...
   Setting up libtypes-serialiser-perl (1.01-1) ...
   Setting up libjson-perl (4.04000-1) ...
   Setting up sysstat (12.5.2-2ubuntu0.2) ...

   Creating config file /etc/default/sysstat with new version
   update-alternatives: using /usr/bin/sar.sysstat to provide /usr/bin/sar (sar) in auto mode
   Created symlink /etc/systemd/system/sysstat.service.wants/sysstat-collect.timer → /lib/systemd/system/sysstat-collect.timer.
   Created symlink /etc/systemd/system/sysstat.service.wants/sysstat-summary.timer → /lib/systemd/system/sysstat-summary.timer.
   Created symlink /etc/systemd/system/multi-user.target.wants/sysstat.service → /lib/systemd/system/sysstat.service.
   Setting up libjson-xs-perl (4.030-1build3) ...
   Setting up postgresql-common (238) ...
   Adding user postgres to group ssl-cert

   Creating config file /etc/postgresql-common/createcluster.conf with new version
   Building PostgreSQL dictionaries from installed myspell/hunspell packages...
   Removing obsolete dictionary files:
   Created symlink /etc/systemd/system/multi-user.target.wants/postgresql.service → /lib/systemd/system/postgresql.service.
   Setting up postgresql-14 (14.12-0ubuntu0.22.04.1) ...
   Creating new PostgreSQL cluster 14/main ...
   /usr/lib/postgresql/14/bin/initdb -D /var/lib/postgresql/14/main --auth-local peer --auth-host scram-sha-256 --no-instructions
   The files belonging to this database system will be owned by user "postgres".
   This user must also own the server process.

   The database cluster will be initialized with locale "C.UTF-8".
   The default database encoding has accordingly been set to "UTF8".
   The default text search configuration will be set to "english".

   Data page checksums are disabled.

   fixing permissions on existing directory /var/lib/postgresql/14/main ... ok
   creating subdirectories ... ok
   selecting dynamic shared memory implementation ... posix
   selecting default max_connections ... 100
   selecting default shared_buffers ... 128MB
   selecting default time zone ... Etc/UTC
   creating configuration files ... ok
   running bootstrap script ... ok
   performing post-bootstrap initialization ... ok
   syncing data to disk ... ok
   update-alternatives: using /usr/share/postgresql/14/man/man1/postmaster.1.gz to provide /usr/share/man/man1/postmaster.1.gz (postmaster.1.gz) in auto mode
   Setting up postgresql (14+238) ...
   Processing triggers for man-db (2.10.2-1) ...
   Processing triggers for libc-bin (2.35-0ubuntu3.8) ...
   NEEDRESTART-VER: 3.5
   NEEDRESTART-KCUR: 6.5.0-1023-aws
   NEEDRESTART-KEXP: 6.5.0-1023-aws
   NEEDRESTART-KSTA: 1

   No output captured for postgres_service_output
   No output captured for create_db_output
   No output captured for create_admin_user_output

   No output captured for nginx_repo_output
   Reading package lists...
   Building dependency tree...
   Reading state information...
   The following NEW packages will be installed:
   nginx
   0 upgraded, 1 newly installed, 0 to remove and 9 not upgraded.
   Need to get 1141 kB of archives.
   After this operation, 3696 kB of additional disk space will be used.
   Get:1 http://nginx.org/packages/ubuntu jammy/nginx amd64 nginx amd64 1.26.0-1~jammy [1141 kB]
   Fetched 1141 kB in 1s (1534 kB/s)
   Selecting previously unselected package nginx.
   (Reading database ... 67329 files and directories currently installed.)
   Preparing to unpack .../nginx_1.26.0-1~jammy_amd64.deb ...
   ----------------------------------------------------------------------

   Thanks for using nginx!

   Please find the official documentation for nginx here:
   * https://nginx.org/en/docs/

   Please subscribe to nginx-announce mailing list to get
   the most important news about nginx:
   * https://nginx.org/en/support.html

   Commercial subscriptions for nginx are available on:
   * https://nginx.com/products/

   ----------------------------------------------------------------------
   Unpacking nginx (1.26.0-1~jammy) ...
   Setting up nginx (1.26.0-1~jammy) ...
   Created symlink /etc/systemd/system/multi-user.target.wants/nginx.service → /lib/systemd/system/nginx.service.
   Processing triggers for man-db (2.10.2-1) ...
   NEEDRESTART-VER: 3.5
   NEEDRESTART-KCUR: 6.5.0-1023-aws
   NEEDRESTART-KEXP: 6.5.0-1023-aws
   NEEDRESTART-KSTA: 1
```
