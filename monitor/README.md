## 3. Health Check

Dalam pengelolaan server, ansible juga digunakan untuk melakukan
healthcheck yang bertujuan untuk memantau resource usage yang
digunakan pada server tersebut.

## Pemeriksaan Kesehatan

Playbook `monitor_client.yml` digunakan untuk melakukan pemeriksaan kesehatan pada sistem. Dengan playbook ini, Anda dapat memverifikasi status layanan dan memastikan bahwa semua komponen sistem berfungsi dengan baik.

![image](https://github.com/user-attachments/assets/218e20fc-5696-4c15-bb7b-fe491943b285)


- **File**: [monitor_client.yml](monitor_client.yml)
- **Deskripsi**: Pada task di atas output dari hasil Healthcheck target host tersimpan ke sebuah direktori `output` dalam bentuk file `.csv`
