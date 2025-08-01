FROM sailugr/sinergym

RUN apt update && apt install

ENV TZ=Asia/Tokyo

RUN python3 -m pip install --upgrade pip \
&& pip install --no-cache-dir \
jupyterlab \
jupyterlab_code_formatter \
torch \
torchvision \
torchaudio

