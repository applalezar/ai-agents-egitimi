İlk MCP Sunucunuzu Kurun: Yönetimi Bırakın
Bu yapay zeka aracı, insan kaynakları departmanına izin yönetimiyle ilgili görevlerde yardımcı olur. Buradaki kod tabanı, sahte izin veritabanıyla etkileşim kuran ve MCP istemci sorgularına yanıt veren MCP sunucusu içindir.

Kurulum adımları
Claude Desktop'ı yükleyin
UV'yi çalıştırmak için yükleyin.pip install uv
uv init my-first-mcp-serverProje dizini oluşturmak için çalıştırın.
uv add "mcp[cli]"Projenize mcp CLI'yı eklemek için çalıştırın.
pip install --upgrade typerBazı kişilerde tür hataları oluşabilir; bu durumda TypeR kütüphanesini en son sürüme yükseltmek için komut çalıştırabilirsiniz.
İzin yönetimi sunucusu için main.py dosyasına kod yazın.
uv run mcp install main.pyProje dizininde aşağıdaki komutu çalıştırarak bu sunucuyu Claude masaüstüne kurun.
Görev Yöneticisi'nden Claude'un çalışan tüm örneklerini sonlandırın. Claude Desktop'ı yeniden başlatın.
Claude masaüstünde artık bu sunucuya ait araçları göreceksiniz.

©Tüm hakları saklıdır. Lalezar Yazılım  
