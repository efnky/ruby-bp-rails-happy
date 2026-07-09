# ruby-bp-rails-happy  (✅)

Bölüm 7 — Buildpack-özel Ruby (Dockerfile YOK): Rails + Gemfile.lock + Procfile,
package.json YOK → jammy-full buildpack happy-path (High uyum) beklentisi.
Not: production.rb'de assume_ssl açık + secret_key_base dummy fallback (Rails-prod
confound nötr) — böylece test yalnız buildpack routing/uyum değişkenini ölçer.
