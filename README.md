# module-5-maplotlib
matplotlib hw module 5
Last login: Mon Sep 11 21:43:19 on ttys000
(base) sophiamendoza@Sophias-Air ~ % cd Desktop
(base) sophiamendoza@Sophias-Air Desktop % git clone https://github.com/SophiaMendoza/module-5-maplotlib.git
Cloning into 'module-5-maplotlib'...
remote: Enumerating objects: 3, done.
remote: Counting objects: 100% (3/3), done.
remote: Compressing objects: 100% (2/2), done.
remote: Total 3 (delta 0), reused 0 (delta 0), pack-reused 0
Receiving objects: 100% (3/3), done.
(base) sophiamendoza@Sophias-Air Desktop % cd module-5-maplotlib
(base) sophiamendoza@Sophias-Air module-5-maplotlib % jupyter notebook

  _   _          _      _
 | | | |_ __  __| |__ _| |_ ___
 | |_| | '_ \/ _` / _` |  _/ -_)
  \___/| .__/\__,_\__,_|\__\___|
       |_|
                       
Read the migration plan to Notebook 7 to learn about the new features and the actions to take if you are using extensions.

https://jupyter-notebook.readthedocs.io/en/latest/migrate_to_notebook7.html

Please note that updating to Notebook 7 might break some of your extensions.

[W 22:47:18.122 NotebookApp] Loading JupyterLab as a classic notebook (v6) extension.
[I 2023-09-11 22:47:18.124 LabApp] JupyterLab extension loaded from /Users/sophiamendoza/anaconda3/lib/python3.11/site-packages/jupyterlab
[I 2023-09-11 22:47:18.124 LabApp] JupyterLab application directory is /Users/sophiamendoza/anaconda3/share/jupyter/lab
[I 22:47:20.841 NotebookApp] The port 8888 is already in use, trying another port.
[I 22:47:20.841 NotebookApp] Serving notebooks from local directory: /Users/sophiamendoza/Desktop/module-5-maplotlib
[I 22:47:20.841 NotebookApp] Jupyter Notebook 6.5.4 is running at:
[I 22:47:20.842 NotebookApp] http://localhost:8889/?token=1173f1b7e9780d16308c7d4b777af2607397476a39f9f741
[I 22:47:20.842 NotebookApp]  or http://127.0.0.1:8889/?token=1173f1b7e9780d16308c7d4b777af2607397476a39f9f741
[I 22:47:20.842 NotebookApp] Use Control-C to stop this server and shut down all kernels (twice to skip confirmation).
[C 22:47:20.845 NotebookApp] 
    
    To access the notebook, open this file in a browser:
        file:///Users/sophiamendoza/Library/Jupyter/runtime/nbserver-17305-open.html
    Or copy and paste one of these URLs:
        http://localhost:8889/?token=1173f1b7e9780d16308c7d4b777af2607397476a39f9f741
     or http://127.0.0.1:8889/?token=1173f1b7e9780d16308c7d4b777af2607397476a39f9f741
0.00s - Debugger warning: It seems that frozen modules are being used, which may
0.00s - make the debugger miss breakpoints. Please pass -Xfrozen_modules=off
0.00s - to python to disable frozen modules.
0.00s - Note: Debugging will proceed. Set PYDEVD_DISABLE_FILE_VALIDATION=1 to disable this validation.
[I 22:49:57.413 NotebookApp] 302 GET /tree (::1) 0.230000ms
[W 22:49:57.452 NotebookApp] 404 GET /apple-touch-icon-precomposed.png (::1) 3.760000ms referer=None
[W 22:49:57.454 NotebookApp] 404 GET /apple-touch-icon.png (::1) 0.560000ms referer=None
[I 22:49:57.468 NotebookApp] 302 GET /tree (::1) 0.250000ms
[W 22:49:57.476 NotebookApp] 404 GET /apple-touch-icon-precomposed.png (::1) 0.550000ms referer=None
[W 22:49:57.477 NotebookApp] 404 GET /apple-touch-icon.png (::1) 0.370000ms referer=None
[I 22:49:57.646 NotebookApp] Writing notebook-signing key to /Users/sophiamendoza/Library/Jupyter/notebook_secret
[W 22:49:57.647 NotebookApp] Notebook pymaceuticals.ipynb is not trusted
[I 22:49:57.976 NotebookApp] Kernel started: 94968ce1-b020-44e1-a64d-df7c521b3da1, name: python3
[W 22:49:58.064 NotebookApp] 404 GET /apple-touch-icon-precomposed.png (::1) 1.000000ms referer=None
[W 22:49:58.066 NotebookApp] 404 GET /apple-touch-icon.png (::1) 1.180000ms referer=None
0.00s - Debugger warning: It seems that frozen modules are being used, which may
0.00s - make the debugger miss breakpoints. Please pass -Xfrozen_modules=off
0.00s - to python to disable frozen modules.
0.00s - Note: Debugging will proceed. Set PYDEVD_DISABLE_FILE_VALIDATION=1 to disable this validation.
[I 22:51:57.964 NotebookApp] Saving file at /pymaceuticals.ipynb
[W 22:51:57.966 NotebookApp] Notebook pymaceuticals.ipynb is not trusted
[I 22:53:57.969 NotebookApp] Saving file at /pymaceuticals.ipynb
[W 22:53:57.970 NotebookApp] Notebook pymaceuticals.ipynb is not trusted
[I 22:55:57.968 NotebookApp] Saving file at /pymaceuticals.ipynb
[W 22:55:57.969 NotebookApp] Notebook pymaceuticals.ipynb is not trusted
[I 22:57:57.995 NotebookApp] Saving file at /pymaceuticals.ipynb
[W 22:57:57.995 NotebookApp] Notebook pymaceuticals.ipynb is not trusted
[I 22:59:57.988 NotebookApp] Saving file at /pymaceuticals.ipynb
[W 22:59:57.989 NotebookApp] Notebook pymaceuticals.ipynb is not trusted
[I 23:01:57.964 NotebookApp] Saving file at /pymaceuticals.ipynb
[W 23:01:57.964 NotebookApp] Notebook pymaceuticals.ipynb is not trusted
[I 23:05:57.967 NotebookApp] Saving file at /pymaceuticals.ipynb
[W 23:05:57.968 NotebookApp] Notebook pymaceuticals.ipynb is not trusted
[I 23:07:57.956 NotebookApp] Saving file at /pymaceuticals.ipynb
[W 23:07:57.957 NotebookApp] Notebook pymaceuticals.ipynb is not trusted
[I 23:09:57.962 NotebookApp] Saving file at /pymaceuticals.ipynb
[W 23:09:57.963 NotebookApp] Notebook pymaceuticals.ipynb is not trusted
[I 23:15:58.503 NotebookApp] Saving file at /pymaceuticals.ipynb
[W 23:15:58.504 NotebookApp] Notebook pymaceuticals.ipynb is not trusted
[I 23:38:33.531 NotebookApp] Starting buffering for 94968ce1-b020-44e1-a64d-df7c521b3da1:4a51cfb9538648f381dc9b3857351fcb
[W 23:39:04.715 NotebookApp] Notebook pymaceuticals.ipynb is not trusted
[I 23:39:56.286 NotebookApp] Starting buffering for 94968ce1-b020-44e1-a64d-df7c521b3da1:a1bad6910a164b2cb875e4f1b686c0cd

git[W 23:40:23.296 NotebookApp] Notebook pymaceuticals.ipynb is not trusted
[I 23:40:32.221 NotebookApp] Starting buffering for 94968ce1-b020-44e1-a64d-df7c521b3da1:85a04f7817114c3a8f25b0b7dac268f2
[I 23:40:32.225 NotebookApp] Kernel shutdown: 94968ce1-b020-44e1-a64d-df7c521b3da1


git status
git add. 
[I 23:42:23.621 NotebookApp] Saving file at /pymaceuticals.ipynb
[W 23:42:23.622 NotebookApp] Notebook pymaceuticals.ipynb is not trusted

[W 23:43:17.373 NotebookApp] 404 DELETE /api/sessions/3b556543-6ecc-408f-ae21-6700521fb95e (::1): Session not found: session_id='3b556543-6ecc-408f-ae21-6700521fb95e'
[W 23:43:17.373 NotebookApp] Session not found: session_id='3b556543-6ecc-408f-ae21-6700521fb95e'
[W 23:43:17.373 NotebookApp] 404 DELETE /api/sessions/3b556543-6ecc-408f-ae21-6700521fb95e (::1) 1.110000ms referer=http://localhost:8889/notebooks/pymaceuticals.ipynb
(base) sophiamendoza@Sophias-Air module-5-maplotlib % git add .       
