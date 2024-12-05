Latest Logs From Latest Build
==============================

Generated On: 2024-12-05 06:36:34 UTC

These are the latest logs generated from your latest build.  

.. tip:: 
   Complete logs from all builds can be found `here on GitHub <https://github.com/167594225-myseneca/cyt160-raspberrypi/blob/main/tml-airflow/logs/logs.txt>`_

.. code-block:: 
  :linenos:

  [INFO 2024-12-05_06:34:21] STEP 1: completed - TML system parameters successfully gathered

  [INFO 2024-12-05_06:34:28] STEP 2: Create topics started

  [INFO 2024-12-05_06:34:44] STEP 2: Completed

  [INFO 2024-12-05_06:34:56] STEP 3: producing data started

  [INFO 2024-12-05_06:34:59] MQTT connection established...

  [INFO 2024-12-05_06:35:02] STEP 4: Preprocessing started

  [INFO 2024-12-05_06:35:05] STEP 4: Preprocessing started

  [INFO 2024-12-05_06:35:09] STEP 7: Visualization started

  [INFO 2024-12-05_06:35:15] STEP 7: /Viperviz/viperviz-linux-amd64 0.0.0.0 9005

  [INFO 2024-12-05_06:35:28] STEP 9: Success starting Qdrant.  Here is the run command: docker run -d -p 6333:6333 -v $(pwd)/qdrant_storage:/qdrant/storage:z qdrant/qdrant

  [INFO 2024-12-05_06:35:33] STEP 9: Starting privateGPT

  [INFO 2024-12-05_06:35:35] STEP 8: Starting docker push for: jona.lyn.learning@gmail.com/jonatest-64f6-amd64

  [INFO 2024-12-05_06:35:44] STEP 9: Success starting privateGPT.  Here is the run command: docker run -d -p 8001:8001 --net=host --env PORT=8001 --env GPU=0 --env COLLECTION=tml --env WEB_CONCURRENCY=1 --env CUDA_VISIBLE_DEVICES=0 maadsdocker/tml-privategpt-no-gpu-amd64

  [WARN 2024-12-05_06:35:55] STEP 8: There seems to be an issue creating the container.  Here is the commit command: docker commit 73cc49262a95 jona.lyn.learning@gmail.com/jonatest-64f6-amd64 - message=1.  Container may NOT pushed.

  [WARN 2024-12-05_06:36:15] STEP 8: There may be an issue pushing to Docker Hub, or just wait few seconds to see if the container shows up.  Here is the command: docker push jona.lyn.learning@gmail.com/jonatest-64f6-amd64 - message=1

  [INFO 2024-12-05_06:36:34] STEP 10: Started to build the documentation

  [INFO 2024-12-05_06:36:34] STEP 10: Documentation successfully built on GitHub..Readthedocs build in process and should complete in few seconds


