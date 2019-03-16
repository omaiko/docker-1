FROM ft-rails:on-build

EXPOSE 3000

CMD ["rails", "s", "-b", "0.0.0.0", "-p", "3000"]

# to ckeck this shit:
# 1) `docker build -t mine-file .`
# 2) `docker build -t ex02 .`
# 3) `docker run -it --rm -p 3000:3000 ex02`
# 4) `http://192.168.99.100:3000`
