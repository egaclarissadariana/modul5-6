color_cycle = cycle(["light blue", "light green", "light pink", "light yellow", "light cyan"]) ==> untuk memberikan warna-warna pada telur supaya menarik
c = Canvas(root, width=canvas_width, height=canvas_height, background="deep skyblue") ==> untuk menampilkan warna pada background, lebar, dan tinggi pada game
egg_speed = 500 ==> kecepatan telur saat jatuh
egg_score = 10 ==> skor yang akan di berikan saat telur jatuh ke penangkap/keranjang
egg_height = 55 ==> tinggi telur saat jatuh
egg_width = 45 ==> digunakan untuk kelebaran telur
catcher_color = "blue" ==> untuk memberikan warna pada penangkap/keranjang telur
catcher_width = 100 ==> lebar yang digunakan untuk penangkap/keranjang telur 
catcher_height = 100 ==> tinggi yang digunakan untuk penangkap/keranjang telur
lives_remaining = 3 ==> game ini akan memberikan kesempatan sebanyak 3 kali
score_text = c.create_text(10, 10, anchor="nw", font=game_font, fill="darkblue", ==> menampilkan warna pada skor
def move_eggs(): ==> kolom untuk menggerakan
def check_catch(): ==> tangkapan telur yang terjatuh
if lives_remaining == 0:
        messagebox.showinfo("Game Over!", "Final Score: "+ str(score)) ==> setelah kesempatan yang diberikan habis game akan "game over"
def move_left(event): ==> untuk menggerakan penagkap/keranjang ke kiri
def move_right(event): ==> untuk menggerakan penagkap/keranjang ke kanan
