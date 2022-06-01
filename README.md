echo "Download file down - Tải xuống các tệp windows"
wget -O w7x64.img https://bit.ly/akuhnetw7X64
echo "Tải xuống ngrok"
wget https://bin.equinox.io/c/4VmDzA7iaHb/ngrok-stable-linux-amd64.zip> / dev / null 2> & 1
giải nén ngrok-stable-linux-amd64.zip> / dev / null 2> & 1
read -p 28h2IMqbYG1FLTuy5cNf5qZbdcJ_5GFpm4nJQLbPouuno4axn
nohup ./ngrok tcp 3388 &> / dev / null &
echo Tải xuống tệp từ toigamo.blogspot.com
apt-get install qemu
echo "Chờ"
echo "Đang khởi động Windows"
echo Địa chỉ RDP:
curl --silent --show-error http://127.0.0.1:4040/api/tunnels | sed -nE 's /.* public_url ":" tcp: .. ([^ "] *). * / \ 1 / p'
echo "Ctrl + C để sao chép - Ctrl + C để sao chép"
echo Tên người dùng: akuh
echo Mật khẩu: Akuh.Net
echo "Chờ 1-2 phút để hoàn thành - Chờ 1-2 phút để hoàn thành bot"
echo "Vui lòng không tắt này cửa sổ - Không đóng tab này"
echo "Hãy ủng hộ toigamo.blogspot.com xin cảm ơn"
qemu-system-x86_64 -hda w7x64.img -m 8G -smp core = 4 -net user, hostfwd = tcp :: 3388-: 3389 -net nic -object rng-random, id = rng0, filename = / dev / urandom -device virtio-rng-pci, rng = rng0 -vga vmware -nographic
ngủ 43200
