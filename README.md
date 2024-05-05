## Environment

- python 3.8.19，pip 24.0
- pytorch 1.10.2+
- CUDA 11.8
- pip3 install -r requirements.txt


## How to run program

0. Make sure python and CUDA are installed

    ```
    D:\> python -V
   
    D:\> nvidia-smi
   
    D:\> nvcc -V
    ```

   
1. Enter catalogue

    ```
    D:\> cd KeWang_20215506
    ```

3. Create python virtual environment

    ```
    D:\KeWang_20215506> python -m venv venv
    ```

4. Activate virtual environment

    ```
     D:\KeWang_20215506> venv\Scripts\activate
    ```

6. Install pytorch
   
    > Depending on operate system, virtual environment, and CUDA version, find the installation command at https://pytorch.org/get-started/locally/. My environment are win11、pip、CUDA 11.8.
   
    ```
     (venv)  D:\KeWang_20215506> pip3 install torch torchvision torchaudio --index-url https://download.pytorch.org/whl/cu118
    ```
   
7. Install softwares
   
    ```
     (venv) D:\KeWang_20215506> pip3 install -r requirements.txt
    ```
   
9. Run Program

    ```
    (venv) D:\KeWang_20215506> python main.py
    ```

## Reference
- https://github.com/ultralytics/yolov5/
