-------------------------------
**تانل 6to4 به دو صورت**

![7115070](https://github.com/Azumi67/6TO4-PrivateIP/assets/119934376/cde3ca64-6750-48dc-8a60-001d44bbdd3d)**تانل 6to4 بدون Anycast**


![green-dot-clipart-3](https://github.com/Azumi67/6TO4-PrivateIP/assets/119934376/d30892cf-cd26-4695-886d-9a4a47ade691)**سرور خارج**

  <p align="right">
  <img src="https://github.com/Azumi67/6TO4-PrivateIP/assets/119934376/81a38493-7df2-46f5-b51b-fee1c7e03349" alt="Image" />
</p>
<div dir="rtl">&bull;در متود اول از یک سرور ایران و یک سرور خارج استفاده میکنیم.  </div>
   <div dir="rtl">&bull; کانفیگ تانل را از سرور خارج آغاز میکنیم. آیپی سرور ایران و خارج را وارد نمایید </div>
    <div dir="rtl">&bull; تعداد آیپی که نیاز دارید را وارد نمایید ( ترجیحا 1 عدد )</div>
     <div dir="rtl">&bull; برای اینکه سرویس پینگ فعال شود، لطفا طبق اسکرین شات آیپی ورژن 4 سرور ایران را وارد نمایید</div>
    

----------------------------------------------------

![green-dot-clipart-3](https://github.com/Azumi67/6TO4-PrivateIP/assets/119934376/d30892cf-cd26-4695-886d-9a4a47ade691)**سرور ایران**


  <p align="right">
  <img src="https://github.com/Azumi67/6TO4-PrivateIP/assets/119934376/dae46cda-ae43-474a-b795-2772e355303f" alt="Image" />
</p>
<div dir="rtl">&bull;در متود اول از یک سرور ایران و یک سرور خارج استفاده میکنیم.  </div>
   <div dir="rtl">&bull; کانفیگ تانل را از سرور خارج آغاز میکنیم. آیپی سرور ایران و خارج را وارد نمایید </div>
    <div dir="rtl">&bull; تعداد آیپی که نیاز دارید را وارد نمایید ( ترجیحا 1 عدد )</div>
     <div dir="rtl">&bull; برای اینکه سرویس پینگ فعال شود، لطفا طبق اسکرین شات آیپی ورژن 4 سرور ایران را وارد نمایید</div>


-------------------------------
![7115070](https://github.com/Azumi67/6TO4-PrivateIP/assets/119934376/cde3ca64-6750-48dc-8a60-001d44bbdd3d)**تانل 6to4 با Anycast**

![green-dot-clipart-3](https://github.com/Azumi67/6TO4-PrivateIP/assets/119934376/d30892cf-cd26-4695-886d-9a4a47ade691)**سرور خارج**

  <p align="right">
  <img src="https://github.com/Azumi67/6TO4-PrivateIP/assets/119934376/fddfce1e-7e27-4d39-b3cb-38f5da53c798" alt="Image" />
</p>
<div dir="rtl">&bull;در متود دوم از یک سرور ایران و یک سرور خارج استفاده میکنیم.   </div>
   <div dir="rtl">&bull; کانفیگ تانل را از سرور خارج آغاز میکنیم. آیپی سرور خارج را وارد نمایید </div>
    <div dir="rtl">&bull; تعداد آیپی که نیاز دارید را وارد نمایید ( ترجیحا 1 عدد )</div>
     <div dir="rtl">&bull; برای اینکه سرویس پینگ فعال شود،  آیپی ورژن 4 سرور ایران را وارد نمایید</div>
    <div dir="rtl">&bull; در روش انی کست میتوانید از آیپی ساخته شده در سرور های دیگر هم استفاده کنید اما پایداری بستگی به سرور های شما داره</div>

----------------------------------------------------

![green-dot-clipart-3](https://github.com/Azumi67/6TO4-PrivateIP/assets/119934376/d30892cf-cd26-4695-886d-9a4a47ade691)**سرور ایران**


  <p align="right">
  <img src="https://github.com/Azumi67/6TO4-PrivateIP/assets/119934376/ae470272-77ee-439c-984e-d4e5b4ec6155" alt="Image" />
</p>
<div dir="rtl">&bull;در متود دوم از یک سرور ایران و یک سرور خارج استفاده میکنیم.   </div>
   <div dir="rtl">&bull;  آیپی سرور ایران را وارد نمایید </div>
    <div dir="rtl">&bull; تعداد آیپی که نیاز دارید را وارد نمایید ( ترجیحا 1 عدد )</div>
     <div dir="rtl">&bull; برای اینکه سرویس پینگ فعال شود،  آیپی ورژن 4 سرور ایران را وارد نمایید</div>
    <div dir="rtl">&bull; در روش انی کست میتوانید از آیپی ساخته شده در سرور های دیگر هم استفاده کنید اما پایداری بستگی به سرور های شما داره</div>


----------------


![R (a2)](https://github.com/Azumi67/PrivateIP-Tunnel/assets/119934376/716fd45e-635c-4796-b8cf-856024e5b2b2)
**اسکریپت تانل**
----------------


```
apt install curl -y && bash <(curl -Ls https://raw.githubusercontent.com/amoangelasa/6TO4-PrivateIP_multipleSERVERS/main/6to4.sh --ipv4)
```
