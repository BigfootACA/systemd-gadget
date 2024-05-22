
# Maintainer: BigfootACA <bigfoot@classfun.cn>

pkgname=systemd-gadget
pkgver=0.0.2
pkgrel=1
pkgdesc="USB gadget setup scripts for systemd"
arch=(any)
url="https://github.com/BigfootACA/systemd-gadget"
license=('GPL')
depends=(
	bash
	systemd
)
optdepends=(
	"adbd: for Android Debug Bridge gadget function"
	"targetcli-fb: for setup TCM gadget function"
)
backup=(
	etc/default/gadget
)
install=systemd-gadget.install
source=(
	gadget
	gadget-init.sh
	gadget-start.sh
	functions.sh
	sharenet.netdev
	sharenet.network
	gadget.network
	gadget-init.service
	gadget-start.service
	usbgadget-func-acm.service
	usbgadget-func-adb-post.service
	usbgadget-func-adb-pre.service
	usbgadget-func-ecm.service
	usbgadget-func-eem.service
	usbgadget-func-geth.service
	usbgadget-func-gser.service
	usbgadget-func-hid.service
	usbgadget-func-mass@.service
	usbgadget-func-midi.service
	usbgadget-func-ncm.service
	usbgadget-func-obex.service
	usbgadget-func-phonet.service
	usbgadget-func-printer.service
	usbgadget-func-rndis.service
	usbgadget-func-tcm.service
	usbgadget-func-uac1.service
	usbgadget-func-uac2.service
	usbgadget-func-uvc.service
	dev-usb-ffs-adb.mount
)
md5sums=('5c34a543424c246263b9e4bf961cf650'
         '0f912dd210e2affc231a4082a024a47f'
         'fa5269709b700b9f93c3d194ef87e179'
         '2ff8247b8c757e833a0d322665c9d686'
         '3bfa595f1ffab96598e582358bc6f92e'
         '86a63f6031e88304b5c15e33f7515ea3'
         'b3c45ca76479754a3cc405386a2e0c08'
         '082057e4d5059fa4b2a38732e4fe7f40'
         '5d9059e13ffe6a092fbfc6756c6dc16b'
         '555ce85766f5d394ddacbb5fab2f0c8d'
         'ccf2867ac3936aef46e140cdbaae6b1f'
         'b9e97cf5566c45c2240ff5e009b87471'
         '70569a2b742303d83d2b539c9bac8777'
         '80040959e904658ec1e0ee156b26a475'
         '9670c8b58cd1824cef2721406a02f4d2'
         '6e012b597f5f7595e225f21fea943af3'
         'd992773964f412026c49b8cf3bcca990'
         '9c7100bfd5bc1e90ff5ec1eb1f093c5e'
         'b9e5988a1a51739e7eb5655a0dde8120'
         '83e7f2a387fe461b4d110b32f599614f'
         'f81fec370175bc1c5544430747efcda5'
         'b1a059173631122802ac944743fae454'
         '5b2ee8dfa4b8048ce091b14ac9af38c6'
         '9b64e160c7107f9271b09ec4f4a368a9'
         'feb70cdb40ab5b15a947cf3aa2d0f00d'
         'e8df46a9b4bd335480e6d8fca7631b48'
         '1236ca4bbdd2f2547728381a25f564fb'
         'e2d0621f7ecf5685b98c1514a8383eec'
         '88b043377c7ef9441d4ef921683dd62e')
sha256sums=('59d3dc74ee55eafa41b639173ad4d3ccba8dbd83ceed46ab79851bbd40eb5faf'
            '197c070a5076cf31ee8e673a202bd7a6bcd0d3820e96db10b39553ebeaf0a1bc'
            '3afcf1c724d6feb3acd40df81eba7eb5d2bf1cf505cc59ac7e440d84084619cc'
            'b058b5fd3bc8472cc596a51666a25c3e30817fcc5ab332917b3d1ed78b2c5966'
            'e073bc788417bf792f9741ccc10ef0f255d831575e99c7d4c72469471244719f'
            '585906ed7243a8a5c7468de0195cb59693319ca22e66e8bf6cbce455a6d71d51'
            '281a970acb041ea3698d289e2b82f7e4b0cfb2fa4d8713bfda96122e9892436e'
            '8cca5a8c34939200839b97f592547499c68d3814734340d186f2739fed2a7ece'
            'a81125fe7abf10e803b4a1d72f46ffc494052596e2624bc5afde11a04d8e374e'
            '722901ea12ef5edc633ce47ba305ba1dad98b462082fcf2828f9494407085704'
            '6799c4bf7566fe0a2d39ef921abc31c29dc03f69c53f923dcfd556e4234eb285'
            'f7730b59e6f584968b1911eca63f4233b2645a9d2894c1f366c8bd3ed8df2f0d'
            'e6f23b835e8594193a9fa23d573fbd2929f5f8258720b256aca515f2743af57b'
            '500ee31df1dbbcb39eb5705b7fb7714421acf0b5d28350ed10449e97bb7f8578'
            'e79c32f53f103b3ee8939710c11923392ad98e5564a85484416d7c419cda43f5'
            '6af71ac2ec1da3782f55740589ff6081202c7ce160429507ac5db09d589ec85b'
            '1958a0ecf73bdb372939c04ff00b62c01f7337d4a6429c0c63cd2444140d2756'
            '7006c41efe1f11a7ea63c830ef685c0b7c4bfb15d524b7e6e91a73e702403ab5'
            '8a5beb836a13ca56be16f2de1b0bfab9aadf4abc2bcdfd45c3ca0baff4ef87df'
            'a68700e299f912357846dd1f2a0f04a955e560e04340045f655a2b38e079ff80'
            'a03565f94642893276e9894debf471a34d10edf0b5f12321437cfa6cab891faa'
            '3deec9c75fe2666411a67f9ed645bea901a9bd4acb08e3580fc58c7f7964b085'
            '6a6f9f7a744ccbd80a1b06cbe2c574e551c37816c8b85035cae5d330f84e8a32'
            '3aa93c51518407065a502f2fc6a1786e38696212568a5a9192153c9b2b724d9f'
            '926149fca15de5bad8bbf3cb79500759215b1e6bf7c25a82818635b5a24cd6b0'
            'c2a81b235313c0d6a4e5822e8db3a911cb8e88e0f464a432d4226cbf1386677f'
            '0524195accf20bdfaa93f93efa8d8633a99dfeba03b607c09fd9546f487a1550'
            'e12ebf69ad91de22788246eae5878d21e6593168f668f9eacbb85ff6a8eb5e67'
            'bfb2fa2f1e9c8f36dfc4cb7039cfc8d490f8174fb0effbb8a90c2d1aed48fe4c')
sha512sums=('a70667519c6e984c13769d9d44c2f156067c3d38752593c8444391800b39c7dc03963de908555b879fd7f87c1a6a598624cb90693c6e40331e2b2a8910362d72'
            '80aa317dad5f4c191008dc05cfc1ab109370c5d7c89f0d6d263a4fd2c1c2d711df065817ceb4ea38d98399eeace8081c847acb451ad4db40bb4cf9b8fde9d54c'
            'ddd0094ee66b563b6bbce5fb9b2919bd4be51a71462a2127bd51d4fb84873cdd3d4f4879aeb16710ebca29104559ffb7f8fc354101c0490309b9b78dfc287037'
            'a19aef89c8ae6e74bea510bc0d7994961ebad0b30908b58c45428add22437d74803bad07cc0b953dba662e42591964c67662b81494f2a6d7a684f9c238d1cc57'
            '7e86f5721902e56654294d1b00fc79719ad6cd9a6978f94c3f76a9b8fd231b6a20b795e1e261653933e75b7a7dae33f6be39099bf99c3ede67e4ed1282620644'
            '925449a3f62e8bc8fa4ac9e4bcc6b8a975cd97872fc52f29afdb135b833a0c69f99da5c7e966125f17ba0f1ab27e1a471926e19fff9c7492d3d168d127ba11a2'
            'b83db9165f540c026cbb54edb32bb47ef87ea4d88d14220deef08889d28a7afc0de5324683b1c6f58863810e90df1abb3adab12daf4036da1d3ecb7cac01abab'
            '6b574e82870d1775a21ee51ba2cd0839048cca0543e932aea8d5a2d9c0586860dd927c3b30eef51b488ce90df0f986a5f4542925f74f976cf1574db91237efc4'
            'dafebb167060a3277486ef68ab32367f08b4a56e85ce7a066e9fe9d4c1641316f5f1245608f95ec5b91156724d093b11018cf546c1186ccca7497b7a45e7eded'
            'e1502e834fe65050ec4b09d5b862f499d2f54c1dbba23a2b664389225c10083c387c9466d01c5edc139ecf96d745fba5f8ba4fe74f522685d3b0721450ea8129'
            '0a8d617742e6d6f350ae0d8be3a7aafb37f6e03cb4d4383d2c6b9286cc48b92d71032a9848f9e07b10235d6dec4d7155f75ee9f32be8ab8f9e26991e546a4954'
            'fd35ffd900cad249a4ed952f305c59049419a61c971ce85e0200b5886190a1d61260b25080ac48b57795e828aeaa73823bb48dc5d41fa19f03b9215391ca7621'
            '8af7eeb9c2cbe69c5b0034a23f43627fe066c9e7bc21d69802ae1e9ceb94f4f921dad95f202eb9157328773974eb214ee0d7a2f2cf7a51921605c8f61d5a73c9'
            '7e78440cf54820942d84873bce4507bdd7b64586c30c3c520fa4b7076bb64b6d686a221c42290fba56863f45affcbe217cd6bd9b7ef3068ad9926888a3db4a2f'
            '0daa322e95b43187d86a7e10f7bd21f21ddf1f95b885b623506684796f3d3b8d2ffbef36b9ef5dc08cc3e7d4fbac146a22c36b2cb84acb3f0aa6a4d14e9e46aa'
            '26fa4ab420cc15c17af6ef55178621be93915eb1211f53526862921feb626d743a5d8ba46fd7a0f8a0b155cb0f8c26b2a8075b8b171b8053fa7542cc1262be62'
            '86520e7048ee09bbb5cd269bf6cf5a8135ae2acbae21491b3c05a96e80b5e5f28b42b137f19a31953aa1178ffa2a550a3901d5b273c848ac5cccf8c4ddc329a6'
            '2563ba96d21c297eac19b0ebead5c879dc9061f6d20b7fa9fbf33f195a42752e329cfb7f50e87b34a0b9a5fcfbd747f89aa791876397d3f180b5111239f7a98a'
            '4c7183cb633f7b5438038d96e7a2d71664f2d59d1a9b0e46d806f9090421143a12a4536c4dfba7b4b06509cc672feb37da373c1d9baec5a259d73c7f0b15bd95'
            'e8704e85c5a24e5530629421354f1420584d39cd9481c7acd8da3445ea4f156f3723cea62ce40ea6d70b0900a1cb381238608af19d10f68d0d69ea9aa508f4e0'
            'dd979aba8eac0277f280458945192dcef212328a4ad93039631c4d415ed096977af6e252105119c3a48468bcc52d8f803e5ed447de3c00a8cbb446df15085bda'
            'a0054dad58c9eb6b8f54b23f2e2f189a3c1df340db6b971e8b3fdfc5d6411cf575b49c555b68bb200e1231089700dd8db616042c8d71bc900f63859fd0322d2e'
            '676fdbb5c3bf27df162ad86f33ef6e1c44a2712f61225dabc1f8aed156c77af84e20b98954818d5ec69f838d3d053cc5f501a7d83c6e48ad94b326bba0640099'
            '9fdbb84e0d5b3a9a06ca06b8f482f762bfc1d1e11d76acb92caa66c06fc3a96b6befaf805e553906ff1cb2d68363bc8aa12a7965a77b7f8c9306ea4c7280844a'
            '3da26f8bb1c495e60564dd724a98446eabe653f66e931b90f8677d69047d9c8e69ba4f6fd6203f213ac0b59631c98218d28287ef81af8db8fa84ef436665b5be'
            '24fb3e82d0b14dac3739d8db04a706d83a65c3b8277c069f510bfc55323b7e6fe6f5e4356502ff4f27edffeecc64282a80eb8c5651fa6cc197c250f035e785bb'
            '59d5b551c95818a57b44d44be644f9f5c0527fabfeebb5069f8979fbb9d2be881c5718596647df8e97d4395bf2858780c0aea3e87b4940d2ca5d0056679b112c'
            'e6ca70e68f40772d960ac92556bb6efbffa348bc9e6e2d7506224693bf29642cfd80b857f78fa6ce3eb1837d7062b2d8ad039bd53b04223ea9e34fc1af83c101'
            'a97e9684dbef06916ab933d41c6dad6bb0ae21c87d5a4d40fd5cb0a367af4b9698ab175861d6330f5c168c4b8b8f6b7f3e891d783eb39fd1f7206180ec6985ee')

package() {
	install -vDm644 "$srcdir/gadget" -t "$pkgdir/etc/default"
	for i in ${source[@]}
	do	case "$i" in
			*.service|*.path|*.mount|*.target|*.socket)
				install -vDm644 "$i" -t "$pkgdir/usr/lib/systemd/system"
			;;
			*.network|*.netdev)
				install -vDm644 "$i" -t "$pkgdir/usr/lib/systemd/network"
			;;
			*.sh)
				install -vDm644 "$i" -t "$pkgdir/usr/lib/systemd/scripts"
			;;
		esac
	done
	mv "$pkgdir/usr/lib/systemd/system/dev-usb-ffs-adb.mount" "$pkgdir/usr/lib/systemd/system/dev-usb\\x2dffs-adb.mount"
}
