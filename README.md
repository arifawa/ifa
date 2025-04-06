class Mobil:
    def _init_(self, merek, model, tahun, warna):  
        self.merek = merek
        self.model = model
        self.tahun = tahun
        self.warna = warna

    def maju(self):
            print(f"{self.merek} {self.model} {self.tahun} {self.warna} bergerak maju.")
        
    def mundur(self):
        print(f"{self.merek} {self.model} {self.tahun} {self.warna} bergerak mundur.")
        
    def belok_kanan(self):
        print(f"{self.merek} {self.model}  {self.tahun} {self.warna}belok kanan.")
        
    def belok_kiri(self):
        print(f"{self.merek} {self.model} {self.tahun} {self.warna} belok kiri.")

mobil1 = Mobil("Toyota", "Avanza", 2020, "Hitam")
mobil2 = Mobil("Honda", "Civic", 2019, "Merah")

mobil1.maju()
mobil1.mundur()
mobil1.belok_kanan()
mobil1.belok_kiri()

mobil2.maju()
mobil2.mundur()
mobil2.belok_kanan()
mobil2.belok_kiri()
