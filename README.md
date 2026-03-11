# AI Podcast Automation System

Bu proje, yapay zekâ kullanarak otomatik podcast üretimi yapan bir otomasyon sistemidir.

## Proje Amacı

Bu sistem, podcast üretim sürecini otomatik hale getirmek için geliştirilmiştir. 
Yapay zekâ kullanarak podcast metni üretir ve bu metni text-to-speech teknolojisi 
ile seslendirilmiş podcast formatına dönüştürür.

## Sistem Nasıl Çalışır

1. Podcast konusu belirlenir
2. LLM API ile podcast metni üretilir
3. Metin düzenlenir
4. ElevenLabs API kullanılarak metin sese dönüştürülür
5. Podcast çıktısı oluşturulur

## Kullanılan Teknolojiler

- n8n
- LLM API
- ElevenLabs API
- HTTP Request / JSON tabanlı entegrasyon

- ## Sistem Akışı

1. Workflow manuel olarak tetiklenir
2. Podcast metni girilir
3. LLM API ile podcast metni oluşturulur
4. Metin düzenlenir
5. ElevenLabs API ile seslendirme yapılır
6. Podcast çıktısı üretilir

## Proje Yapısı

Bu repoda projenin mimarisi, ekran görüntüleri ve örnek çıktılar paylaşılmaktadır.
