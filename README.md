# Turbyte VDS Benchmark ve Sistem Performans Araçları

Bu depo, **Turbyte Datacenter Services** tarafından Linux sunucular ve sistem yöneticileri için geliştirilmiş performans test betiklerini ve altyapı optimizasyon rehberlerini içerir.

## Hızlı Bağlantılar

* **Resmi Web Sitesi:** [turbyte.net](https://turbyte.net)
* **Yüksek Performanslı VDS Paketleri:** [Turbyte VDS Kiralama](https://turbyte.net/sanal-sunucu-kirala.php)
* **Canlı Altyapı ve Sistem Durumu:** [status.turbyte.net](https://status.turbyte.net)

## Sunucu Benchmark Testi

VDS sunucunuzun CPU, bellek ve adanmış NVMe SSD okuma/yazma (I/O) performansını ölçmek için aşağıdaki komutu kullanabilirsiniz:

```bash
curl -sL [https://turbyte.net/bench.sh](https://turbyte.net/bench.sh) | bash
