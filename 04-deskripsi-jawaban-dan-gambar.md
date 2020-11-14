Perbedaan mencolok Docker dan VMWare
VM menggunakan kernel sendiri sehingga menjadi beban bagi host tetapi
sedangkan Docker membagi kernelnya ke container yang ada. 
Jika dibandingkan dengan VM, secara pengaturan kontainer lebih mudah. 
Hal ini disebabkan karena konsep berbagi resource hardware dari container 
lebih fleksibel bila dibandingkan VM. 

Docker sangat ringan dan cepat jika dibandingkan dengan virtual mesin yang 
berbasis hypervisor, sehingga menjadikan Docker sebagai alternatif yang 
efisien untuk developer tooling.

Docker digunakan ketika developer ingin mendeploy aplikasi sedangkan 
VM digunakan untuk kebutuhan hosting