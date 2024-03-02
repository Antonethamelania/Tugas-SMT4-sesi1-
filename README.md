# Tugas-SMT4-sesi1-
public class HandPhone {

    String jenis_hp;
    int tahun_pembuatan;

    public void setDataHP(String jenis_hp, int tahun_pembuatan) {
        this.jenis_hp = jenis_hp;
        this.tahun_pembuatan = tahun_pembuatan;
    }

    String getJenisHp() {
        return jenis_hp;
    }

    int getTahunPembuatan() {
        return tahun_pembuatan;
    }

    public static void main(String[] args) {
        HandPhone hp = new HandPhone();
        hp.setDataHP("Samsung Galaxy S22", 2022);
        System.out.println("Jenis HP: " + hp.getJenisHp());
        System.out.println("Tahun Pembuatan: " + hp.getTahunPembuatan());
    }
}
Java
public class HandPhone {

    String jenis_hp;
    int tahun_pembuatan;

    public void setDataHP(String jenis_hp, int tahun_pembuatan) {
        this.jenis_hp = jenis_hp;
        this.tahun_pembuatan = tahun_pembuatan;
    }

    String getJenisHp() {
        return jenis_hp;
    }

    int getTahunPembuatan() {
        return tahun_pembuatan;
    }

    public static void main(String[] args) {
        HandPhone hp = new HandPhone();
        hp.setDataHP("Samsung Galaxy S22", 2022);
        System.out.println("Jenis HP: " + hp.getJenisHp());
        System.out.println("Tahun Pembuatan: " + hp.getTahunPembuatan());
    }
}
