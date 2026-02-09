# İlk MCP Sunucunuzu Oluşturun: İzin Yönetimi

Bu yapay zeka aracı, İK departmanının izin yönetimi ile ilgili görevlerinde yardımcı olur. Buradaki kod tabanı, sahte izin veritabanı ile etkileşime giren ve MCP istemci sorgularına yanıt veren bir MCP sunucusu içindir.

## Kurulum Adımları

1. **Claude Desktop'ı Yükleyin**

2. **uv'yi yükleyin**
   ```bash
   pip install uv
   ```

3. **Proje dizini oluşturun**
   ```bash
   uv init my-first-mcp-server
   ```

4. **Projenize MCP CLI ekleyin**
   ```bash
   uv add "mcp[cli]"
   ```

5. **Tür hatalarını düzeltin** (bazı kişiler için gerekli olabilir)
   ```bash
   pip install --upgrade typer
   ```
   Typer kütüphanesini en son sürümüne yükseltin

6. **İzin yönetimi sunucusu için `main.py` dosyasına kod yazın**

7. **Bu sunucuyu Claude Desktop içine kurun**
   ```bash
   uv run mcp install main.py
   ```
   Proje dizininde bu komutu çalıştırın

8. **Claude'un çalışan tüm örneklerini kapatın**
   Görev Yöneticisi'nden (Task Manager) kapatın

9. **Claude Desktop'ı yeniden başlatın**

10. **Araçları görüntüleyin**
    Claude Desktop'ta artık bu sunucudan gelen araçları görebileceksiniz

©Tüm hakları saklıdır. Lalezar Yazılım  
