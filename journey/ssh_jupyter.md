# Use Jupyter Notebook from remote machine

In the EC2 instance:
```sh
$ jupyter notebook --no-browser --port=8888

```

Open a new terminal and SSH to the Jupyter Notebook.
```sh
$ ssh mlops-zoomcamp -L 8000:localhost:8888
```

Then open the browser and go to `localhost:8000`
