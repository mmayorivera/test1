while [ ! -z "`ps -e | grep 'apt\|dpkg'`" ]; do echo "Waiting for apt or dpkg to exit."; sleep 6; done && \
sudo apt-get update && sudo apt-get -y install ca-certificates wget && \
sudo wget -nv -O serverpilot-installer https://download.serverpilot.io/serverpilot-installer && \
sudo sh serverpilot-installer \
    --server-id=FLQeUiEbdEcajM4M \
    --server-apikey=d5zQ7GqSqsRLpb5RVlkF86grXcLMvC8o60yiyH7vX5A




ssh-rsa AAAAB3NzaC1yc2EAAAADAQABAAABAQCzD9Eb9CmJzXCBYhJV55iJZouxmO3hwDx1lUJIknt+qpipBaiYJkg1+lJa2z6bNBwEaLvxUcMoIMIFMWnz8pkJZQ/TdscOhA9OuKs6FNXTfBSkA/m986KLQSEM7N5S55Cs7eF0hLq5m0QAoXzL/OYzk4Nr/wPNRvzCt2HXfu1tt5P+oA5fXkj15ZfGF0QuSQRXKmfydahLlm2lsTsr9piSWaWIeBaiHGtQtxDzjynPMHh9qhZIde5+JXeYEYqROWNZYxx8Z8nsBGKpQWMk2ZQF+BUwKSDwWv+3DNKlkB5AcXJ4vtaLY/yiprkIfb/fw47159FZxn0E1wB62gaKaAll redefin3d@Ralphs-MBP
