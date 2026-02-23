# JAKARTA-EE-Introduction
Jakarta EE,ilgari Java Platform,  Enterprise Edition (Java EE) va Java 2 Platform ,Enterprise (J2EE) deb atalgan ,Java SE ni kengaytiruvchi va korporativ xususiyatlar ,maslan, taqsimalangan  xizmatla uchun spetsifikatsiylar to'plmadir..
2001 -yilda J2EE 1.3 versiyasi chiqariladi .bu platformaga ko'proq platformaga spetsifikatsiyalar qo'shdi. Server Pages Standard Tag Library (JSTL) va Java Authentication and Authorization Srvice (JAAS).Java Servletlar kabi boshqa spetsifikatsiyalar ham J2EE 1.3 versiyasida takomilashtirib ,platformaga evolyutsion yaxshilanishlar kiritildi.
2003 -yilda J2EE  1.3 versiyasi chiqarilarilishi  Java Enterprise uchun muhim bosqich bo'ldi,
chunki playformaga ko'plab yangi spetsifikatsiyalar qo'shildi va bu Java texnologiyalar uchun standartlarni kengaytiradi yanada kengaytiradi.J2EE 1.4 versiyasi Web Services for J2EE 1.1 , Java Server Faces va JAXP ,JAXR kabi XML yechimlari uchun Java APIlarning birinchi iteretsiyalarni taqdim etadi.J2EE 1.4 versiyasi ko'plab spetsifikatsiyalarni o'z ichiga olgan bo'lsada , u hali ham "o'rganish qiyin ",""og'i" va "samarali emas " deb hisoblanardi.Keyingi bir necha yil ichida J2EE zamonaviy veb -ilovalarni yaratishda osonroq qo'lllash uchun qayta ishlab chiqildi.
2006 -yil may oyida Sun Microsytems J2EE akronimni tashlab ,uning o'rniga oddiygina Java EE deb nomlangan Java EE5  versiyasini chiqardi.Java EE5 platformasi foydalanish va boshqarish ancha oson edi,chunki u annotatsiyalar kabi xususiyatlar joriy etdi, bu XML konfiguratsiyasi miqdorini sezilarli darajada qisqartirdi.
JAKARTA EE
Sun MicroSystems 'ni sotib olgandan so'ng .Oracle Corporation 2009 -yilda Java  EE6 ni chiqaradi,bu konfiguratsiya va API 'LARNI yanada osonlashtiradi va platformaga ko'proq spetsifikatsiyalar qo'shildi .Contexts and Dependency Injection (CDI) va Bean Validation kabi 
spetsifikatsiyalar joriy etildi,bu plaformaning  manzarasini sezilarli darajada  o'zgartirdi va ishlab chiqish jarayonini soddalashtirdi.
2013 -yilda chiqarilgan Java EE 7 platformani yanada mustahkamlaash va modernizatsiya qilishini davom ettirdi , WebSockets va Json-P spetsifikatsiyalarni qo'shdi.
Java EE 8 chiqishdan oldin Oracle Java EE NI ochiq  manba sifatida taqdim etishini elon qildi. Oracle barcha Java EE manbalarini (har bir asosiy spetsifikatsiya uchun) taqdim etishini ham e'lon qildi.
2017 -yil oxirida EE4J (Eclipse Enterprise for Java )loyihasini tashkil etildi  va har bir spetsifikatsiyani o'tkazish jarayoni boshlanadi.
2019 -yil 10 sentabrda Jakarta EE8 chiqariladi.
2020 -yil noyabr oyida Eclipse Foundation Jakarta EE9 chiqardi. BU versiyada platformada muhim o'zgarishlar yo'q edi. Eng muhim bosqich barcha APIlarni taqdim 'javax' nomlari fazosiga ko'chrish bo'ldi, chunki savdo belgisi cheklovlari tufayli 'javax ' nomlar fazosida o'zgartirish kiritishga ruxsat berilmagan edi.
2021 - yil fevral oyida Eclipse Foundation Jakarta EE 9.1 chiqardi.Jakarta EE 9.1 Jakarta EE.9 asosida Java SE 11 qo'llab quvatlashni qo'shdi.

SPESIFICATIONS
Jakarta EE truli maqsadlarga xizmat qiluvchi bir nechta  spetsifikatsiyalarni o'z ichiga oladi masalan ,veb -sahifalarni yaratish ,malumotlar bazasidan tranzaksiyali tarzda  o'qish va yozish ,taqsimlangan navbatlarni boshqarish.
Jakarta EE API larni Java SE APIlarni funksionaligi kengayturuvchi  bir nechta texnologiyalarni o'z ichiga oladi, masalan ,Jakarta Enterprise Beans, connectors,servlets, Jakarta Server Pages va bir nechta veb-xizmat taxnologiyalari.

WEB SPECIFICATIONS
Jakarta Servelet -Http so'rovlarini sinxron yoki azinxron tarzda boshqarishni blgilaydi.Bu past darajali  spetsifikatsiya bo'lib ,boshqa Jakarta EE spetsifikatsiyalarga tayanadi.
Jakarta WebSocket -WebSocket ulanishlarni xizmat ko'rsatish uchun APIlar to'plamini belgilovchi API spetsifikatsiya.
Jakarta Servelets(Ilgari Java Servelets) -dinamik veb -ilovalarni yaraish uchun texnologiya.
Jakarta Server Faces- komponentlardan foydalanib  foydalanuvchi interfeyslarni qurish uchun texnologiya .

Jakarta Expression Language (EL)- veb -ilova ishlab chiquvchilarning maxsus ehtiyojlarini qondirish uchun mo'ljalalangan oddiy til. U xususan ,Jakarta Faces'da komponentlarni(backing) bean'lar bilan bog'lash va Contexts and Dependency Injection'da nomlangan beanlar uchun ishlatiladi,lekin butun platformani qo'llanilishi mumkin.
    WEB SERVICE SPECIFICATIONS 
Jakarta REStful Web Services -Representational State Transfer (REST) arxitektura naqshiga muvofiq  veb-xizmatlarni yaratishni qo'llab quvvatlaydi.
Jakarta JSON processing -JSON formatida kodlangan ma'lumotlarni boshqarish uchun spetsifikatsiyalar to'plami.
Jakarta Json Binding -JSON ma'lumotlarini Java sinflariga aylantirish yoki Java sinflaridan JSON ma'lumotlariga aylantirish uchun spetsifkatsiyalarni taqdim etadi.
Jakarta XML Binding -XML'ni Java obe'ktlaga moslashtirish imkonini beradi.
Jakarta XML Web Services -SOAP veb-xizmatlarni yaratish uchun ishlatilishi mumkin.
Enterprise Specifications 
Jakarta Contexts and Depebdency Injection(CDI)- bu dependency injection (bog'iqlik kiritish) konteynerni taqdim etuvchi spetsifikatsiya .
Jakarta Enterprise Beans(EJB) spetsifikatsiyasi biznes ob'ektlari uchun tranzaksiyalari (JTA yordamida ), masofaviy  protsedura chaquruvlari (  RMI yoki RMI-IIOP yordamida ), parallel boshqaruv ,dependency injection va kirish nazoratini taminlash uchun ob'ekt konteyneri (EJB konteyneri) tomonidan qo'llab quvatlanadigan yengil  API lari to'plamini belgilaydi .Ushbu paket eneerprise bean va uning mijozlari o'rtasidagi , shuningdek enterprise bean va EJB konteyneri o'rtasiadgi  shartnomani  belgilovchi  Jakarta Enterprise Beans sinflari va interfeyslarini o'z ichiga oladi.
Jakarta Persistence(JPA) - bu relational ma'lumotlar bazasi jadvallari va Java sinflari o'rtasida obe'kt relational mapping (ORM) haqidagi spetsifikatsiyalar.
Jakarta Transactions (JTA)- Jakarta EE tomonidan taqimd etilgan tranzaksiya qo'llab quvvatlash bilan o'zaro aloqa qilish uchun interfeyslar va annotatsiyalar o'z ichiga oladi. Ushbu API juda 
past darajali hisoblanadi va Jakarte EE dagi o'rtacha ilova ishlab chiqariuvchisi tranzaksiyalarni yuqori darajali EJB abstraktsiyalar orqali shaffof boshqarishga tayanadi yoki ushbu  API tominidan taqdim etilgan annotatiyalrni  CDI boshqaradigan beanlar bilan birgalikda ishlatadi.
Jakarta Messaging (JMS) -Java dasturlari uchun korporativ xabar almashish tizimning xabarlarini yaratish, yuborish, qabul qilish uchun amaliy usulini taqdim etadi.
Jakarta Standard Tag Library (JSTL) - To'liq misollar
Quyida har bir teg guruhi (Core, Formatting, SQL, Function, XML) va ularning teglari uchun misollar keltiriladi.

JSTL Tags Table is here.
JSTLni sozlash
JSTL ishlatish uchun loyihangizga quyidagi dependency'larni qo'shing:

<dependency>
    <groupId>jakarta.servlet.jsp.jstl</groupId>
    <artifactId>jakarta.servlet.jsp.jstl-api</artifactId>
    <version>3.0.0</version>
</dependency>
<dependency>
    <groupId>org.glassfish.web</groupId>
    <artifactId>jakarta.servlet.jsp.jstl</artifactId>
    <version>3.0.1</version>
</dependency>
JSP sahifalarida teglarni ishlatish uchun mos direktivalarni qo'shing, masalan:

<%@ taglib prefix="c" uri="jakarta.tags.core" %>
Batafsil ma'lumot uchun: Jakarta EE JSTL Tag Dokumentatsiyasi

1. Core Tags - Tags Table
Core teglar c prefiksi bilan ishlatiladi va umumiy vazifalarni bajaradi.

<c:out> - Qiymatni chiqarish
<%@ page language="java" contentType="text/html; charset=UTF-8" pageEncoding="UTF-8"%>
<%@ taglib prefix="c" uri="jakarta.tags.core" %>
<!DOCTYPE html>
<html>
<head>
    <title>c:out Misoli</title>
</head>
<body>
    <h1>c:out Misoli</h1>
    <c:set var="matn" value="<b>Salom, Dunyo!</b>" scope="request"/>
    <p>Xavfsiz chiqish: <c:out value="${matn}" escapeXml="true"/></p>
    <p>Xavfsiz bo'lmagan chiqish: <c:out value="${matn}" escapeXml="false"/></p>
    <p>Standart qiymat: <c:out value="${bo'lmaganMatn}" default="Qiymat topilmadi"/></p>
</body>
</html>
Tushuntirish: <c:out> EL ifodasini chiqaradi, escapeXml="true" XSS hujumlaridan himoya qiladi.

<c:set> - O'zgaruvchini o'rnatish
<%@ page language="java" contentType="text/html; charset=UTF-8" pageEncoding="UTF-8"%>
<%@ taglib prefix="c" uri="jakarta.tags.core" %>
<!DOCTYPE html>
<html>
<head>
    <title>c:set Misoli</title>
</head>
<body>
    <h1>c:set Misoli</h1>
    <c:set var="ism" value="Ali" scope="session"/>
    <p>O'rnatilgan o'zgaruvchi: <c:out value="${ism}"/></p>
    <c:set var="son" value="${5 + 3}"/>
    <p>Hisoblangan qiymat: <c:out value="${son}"/></p>
</body>
</html>
Tushuntirish: <c:set> o'zgaruvchilarni turli sohalarda (scope) saqlaydi.

<c:remove> - O'zgaruvchini o'chirish
<%@ page language="java" contentType="text/html; charset=UTF-8" pageEncoding="UTF-8"%>
<%@ taglib prefix="c" uri="jakarta.tags.core" %>
<!DOCTYPE html>
<html>
<head>
    <title>c:remove Misoli</title>
</head>
<body>
    <h1>c:remove Misoli</h1>
    <c:set var="ism" value="Vali" scope="session"/>
    <p>O'chirishdan oldin: <c:out value="${ism}" default="Topilmadi"/></p>
    <c:remove var="ism" scope="session"/>
    <p>O'chirishdan keyin: <c:out value="${ism}" default="Topilmadi"/></p>
</body>
</html>
Tushuntirish: <c:remove> belgilangan sohada saqlangan o'zgaruvchini o'chiradi.

<c:catch> - Xatolarni ushlash
<%@ page language="java" contentType="text/html; charset=UTF-8" pageEncoding="UTF-8"%>
<%@ taglib prefix="c" uri="jakarta.tags.core" %>
<!DOCTYPE html>
<html>
<head>
    <title>c:catch Misoli</title>
</head>
<body>
    <h1>c:catch Misoli</h1>
    <c:catch var="xato">
        <% int x = 1 / 0; %>
    </c:catch>
    <c:if test="${not empty xato}">
        <p>Xato yuz berdi: <c:out value="${xato.message}"/></p>
    </c:if>
</body>
</html>
Tushuntirish: <c:catch> ichidagi xatolarni ushlaydi va xato ma'lumotlarini o'zgaruvchiga saqlaydi.

<c:if> - Shartli bajarish
<%@ page language="java" contentType="text/html; charset=UTF-8" pageEncoding="UTF-8"%>
<%@ taglib prefix="c" uri="jakarta.tags.core" %>
<!DOCTYPE html>
<html>
<head>
    <title>c:if Misoli</title>
</head>
<body>
    <h1>c:if Misoli</h1>
    <c:set var="son" value="7"/>
    <c:if test="${son > 5}">
        <p>Son 5 dan katta!</p>
    </c:if>
    <c:if test="${son < 5}">
        <p>Son 5 dan kichik!</p>
    </c:if>
</body>
</html>
Tushuntirish: <c:if> shart to'g'ri bo'lsa, ichidagi tarkibni bajaradi.

<c:choose>, <c:when>, <c:otherwise> - Shartli logika
<%@ page language="java" contentType="text/html; charset=UTF-8" pageEncoding="UTF-8"%>
<%@ taglib prefix="c" uri="jakarta.tags.core" %>
<!DOCTYPE html>
<html>
<head>
    <title>c:choose Misoli</title>
</head>
<body>
    <h1>c:choose, c:when, c:otherwise Misoli</h1>
    <c:set var="son" value="10"/>
    <c:choose>
        <c:when test="${son == 10}">
            <p>Son 10 ga teng!</p>
        </c:when>
        <c:when test="${son > 10}">
            <p>Son 10 dan katta!</p>
        </c:when>
        <c:otherwise>
            <p>Son 10 dan kichik!</p>
        </c:otherwise>
    </c:choose>
</body>
</html>
Tushuntirish: <c:choose> shartli logika uchun kontekst yaratadi, <c:when> shartlarni tekshiradi, <c:otherwise> qolgan holatlarni qamrab oladi.

<c:import> - URL tarkibini import qilish
<%@ page language="java" contentType="text/html; charset=UTF-8" pageEncoding="UTF-8"%>
<%@ taglib prefix="c" uri="jakarta.tags.core" %>
<!DOCTYPE html>
<html>
<head>
    <title>c:import Misoli</title>
</head>
<body>
    <h1>c:import Misoli</h1>
    <c:import var="tarkib" url="https://www.example.com"/>
    <p>Import qilingan tarkib: <c:out value="${tarkib}" escapeXml="true"/></p>
</body>
</html>
Tushuntirish: <c:import> URL'dan tarkibni oladi va uni o'zgaruvchiga saqlaydi yoki chiqaradi.

<c:forEach> - To'plamlar bo'yicha aylanish
<%@ page language="java" contentType="text/html; charset=UTF-8" pageEncoding="UTF-8"%>
<%@ taglib prefix="c" uri="jakarta.tags.core" %>
<!DOCTYPE html>
<html>
<head>
    <title>c:forEach Misoli</title>
</head>
<body>
    <h1>c:forEach Misoli</h1>
    <%
        java.util.List<String> royxat = java.util.Arrays.asList("Ali", "Vali", "Sardor");
        request.setAttribute("foydalanuvchilar", royxat);
    %>
    <ul>
        <c:forEach var="ism" items="${foydalanuvchilar}" begin="0" end="1">
            <li><c:out value="${ism}"/></li>
        </c:forEach>
    </ul>
</body>
</html>
Tushuntirish: <c:forEach> ro'yxatni aylanib chiqadi va elementlarni chiqaradi.

<c:forTokens> - Tokenlar bo'yicha aylanish
<%@ page language="java" contentType="text/html; charset=UTF-8" pageEncoding="UTF-8"%>
<%@ taglib prefix="c" uri="jakarta.tags.core" %>
<!DOCTYPE html>
<html>
<head>
    <title>c:forTokens Misoli</title>
</head>
<body>
    <h1>c:forTokens Misoli</h1>
    <c:set var="matn" value="Ali,Vali,Sardor"/>
    <ul>
        <c:forTokens var="ism" items="${matn}" delims=",">
            <li><c:out value="${ism}"/></li>
        </c:forTokens>
    </ul>
</body>
</html>
Tushuntirish: <c:forTokens> matnni ajratgichlar orqali tokenlarga bo'ladi va aylanib chiqadi.

<c:param> - URL parametrlarni qo'shish
<%@ page language="java" contentType="text/html; charset=UTF-8" pageEncoding="UTF-8"%>
<%@ taglib prefix="c" uri="jakarta.tags.core" %>
<!DOCTYPE html>
<html>
<head>
    <title>c:param Misoli</title>
</head>
<body>
    <h1>c:param Misoli</h1>
    <c:url var="url" value="/boshqa_sahifa.jsp">
        <c:param name="ism" value="Ali"/>
        <c:param name="yosh" value="25"/>
    </c:url>
    <p>URL: <a href="${url}"><c:out value="${url}"/></a></p>
</body>
</html>
Tushuntirish: <c:param> <c:url> yoki <c:import> ichida URL'ga parametr qo'shadi.

<c:redirect> - Yo'naltirish
<%@ page language="java" contentType="text/html; charset=UTF-8" pageEncoding="UTF-8"%>
<%@ taglib prefix="c" uri="jakarta.tags.core" %>
<!DOCTYPE html>
<html>
<head>
    <title>c:redirect Misoli</title>
</head>
<body>
    <h1>c:redirect Misoli</h1>
    <c:redirect url="/boshqa_sahifa.jsp">
        <c:param name="xabar" value="Yo'naltirish muvaffaqiyatli!"/>
    </c:redirect>
</body>
</html>
Tushuntirish: <c:redirect> yangi URL'ga yo'naltiradi.

<c:url> - URL yaratish
<%@ page language="java" contentType="text/html; charset=UTF-8" pageEncoding="UTF-8"%>
<%@ taglib prefix="c" uri="jakarta.tags.core" %>
<!DOCTYPE html>
<html>
<head>
    <title>c:url Misoli</title>
</head>
<body>
    <h1>c:url Misoli</h1>
    <c:url var="url" value="/boshqa_sahifa.jsp">
        <c:param name="ism" value="Sardor"/>
    </c:url>
    <p>URL: <a href="${url}"><c:out value="${url}"/></a></p>
</body>
</html>
Tushuntirish: <c:url> parametrlar bilan URL yaratadi.

2. Formatlash teglari (Formatting Tags) - Tags Table
Formatlash teglari fmt prefiksi bilan ishlatiladi va sana, raqamlar va xalqarolashtirish uchun ishlatiladi.

<fmt:formatNumber> - Raqamni formatlash
<%@ page language="java" contentType="text/html; charset=UTF-8" pageEncoding="UTF-8"%>
<%@ taglib prefix="fmt" uri="http://java.sun.com/jsp/jstl/fmt" %>
<!DOCTYPE html>
<html>
<head>
    <title>fmt:formatNumber Misoli</title>
</head>
<body>
    <h1>fmt:formatNumber Misoli</h1>
    <c:set var="raqam" value="12345.6789"/>
    <p>Oddiy format: <fmt:formatNumber value="${raqam}" maxFractionDigits="2"/></p>
    <p>Valyuta: <fmt:formatNumber value="${raqam}" type="currency"/></p>
    <p>Foiz: <fmt:formatNumber value="${raqam}" type="percent"/></p>
</body>
</html>
Tushuntirish: <fmt:formatNumber> raqamni turli formatlarda chiqaradi.

<fmt:parseNumber> - Raqamni tahlil qilish
<%@ page language="java" contentType="text/html; charset=UTF-8" pageEncoding="UTF-8"%>
<%@ taglib prefix="fmt" uri="http://java.sun.com/jsp/jstl/fmt" %>
<!DOCTYPE html>
<html>
<head>
    <title>fmt:parseNumber Misoli</title>
</head>
<body>
    <h1>fmt:parseNumber Misoli</h1>
    <c:set var="raqamMatn" value="12,345.67"/>
    <fmt:parseNumber var="raqam" value="${raqamMatn}" pattern="##,###.##"/>
    <p>Tahlil qilingan raqam: <c:out value="${raqam}"/></p>
</body>
</html>
Tushuntirish: <fmt:parseNumber> matnli raqamni son sifatida tahlil qiladi.

<fmt:formatDate> - Sanani formatlash
<%@ page language="java" contentType="text/html; charset=UTF-8" pageEncoding="UTF-8"%>
<%@ taglib prefix="fmt" uri="http://java.sun.com/jsp/jstl/fmt" %>
<!DOCTYPE html>
<html>
<head>
    <title>fmt:formatDate Misoli</title>
</head>
<body>
    <h1>fmt:formatDate Misoli</h1>
    <%
        request.setAttribute("hozir", new java.util.Date());
    %>
    <p>Sana: <fmt:formatDate value="${hozir}" pattern="dd-MM-yyyy HH:mm:ss"/></p>
    <p>Vaqt: <fmt:formatDate value="${hozir}" type="time"/></p>
</body>
</html>
Tushuntirish: <fmt:formatDate> sanani belgilangan formatda chiqaradi.

<fmt:parseDate> - Sanani tahlil qilish
<%@ page language="java" contentType="text/html; charset=UTF-8" pageEncoding="UTF-8"%>
<%@ taglib prefix="fmt" uri="http://java.sun.com/jsp/jstl/fmt" %>
<!DOCTYPE html>
<html>
<head>
    <title>fmt:parseDate Misoli</title>
</head>
<body>
    <h1>fmt:parseDate Misoli</h1>
    <c:set var="sanaMatn" value="20-06-2025"/>
    <fmt:parseDate var="sana" value="${sanaMatn}" pattern="dd-MM-yyyy"/>
    <p>Tahlil qilingan sana: <fmt:formatDate value="${sana}" pattern="yyyy-MM-dd"/></p>
</body>
</html>
Tushuntirish: <fmt:parseDate> matnli sanani Date ob'ektiga aylantiradi.

<fmt:bundle> va <fmt:message> - Xalqarolashtirish
<%@ page language="java" contentType="text/html; charset=UTF-8" pageEncoding="UTF-8"%>
<%@ taglib prefix="fmt" uri="http://java.sun.com/jsp/jstl/fmt" %>
<!DOCTYPE html>
<html>
<head>
    <title>fmt:bundle va fmt:message Misoli</title>
</head>
<body>
    <h1>fmt:bundle va fmt:message Misoli</h1>
    <fmt:setLocale value="uz_UZ"/>
    <fmt:bundle basename="messages">
        <p>Xabar: <fmt:message key="salom"/></p>
    </fmt:bundle>
</body>
</html>
messages.properties fayli:

salom=Xush kelibsiz, Dunyo!
Tushuntirish: <fmt:bundle> resurs to'plamini yuklaydi, <fmt:message> xalqarolashtirilgan xabarni chiqaradi.

<fmt:setLocale> - Til sozlamasini o'rnatish
<%@ page language="java" contentType="text/html; charset=UTF-8" pageEncoding="UTF-8"%>
<%@ taglib prefix="fmt" uri="http://java.sun.com/jsp/jstl/fmt" %>
<!DOCTYPE html>
<html>
<head>
    <title>fmt:setLocale Misoli</title>
</head>
<body>
    <h1>fmt:setLocale Misoli</h1>
    <fmt:setLocale value="uz_UZ"/>
    <fmt:bundle basename="messages">
        <p>O'zbek tilida: <fmt:message key="salom"/></p>
    </fmt:bundle>
    <fmt:setLocale value="en_US"/>
    <fmt:bundle basename="messages">
        <p>Ingliz tilida: <fmt:message key="salom"/></p>
    </fmt:bundle>
</body>
</html>
Tushuntirish: <fmt:setLocale> til sozlamasini o'zgartiradi.

<fmt:setBundle> - Resurs to'plamini o'rnatish
<%@ page language="java" contentType="text/html; charset=UTF-8" pageEncoding="UTF-8"%>
<%@ taglib prefix="fmt" uri="http://java.sun.com/jsp/jstl/fmt" %>
<!DOCTYPE html>
<html>
<head>
    <title>fmt:setBundle Misoli</title>
</head>
<body>
    <h1>fmt:setBundle Misoli</h1>
    <fmt:setBundle basename="messages" var="bundle"/>
    <fmt:message bundle="${bundle}" key="salom"/>
</body>
</html>
Tushuntirish: <fmt:setBundle> resurs to'plamini o'zgaruvchiga saqlaydi.

<fmt:timeZone> va <fmt:setTimeZone> - Vaqt mintaqasi
<%@ page language="java" contentType="text/html; charset=UTF-8" pageEncoding="UTF-8"%>
<%@ taglib prefix="fmt" uri="http://java.sun.com/jsp/jstl/fmt" %>
<!DOCTYPE html>
<html>
<head>
    <title>fmt:timeZone va fmt:setTimeZone Misoli</title>
</head>
<body>
    <h1>fmt:timeZone Misoli</h1>
    <%
        request.setAttribute("hozir", new java.util.Date());
    %>
    <fmt:timeZone value="Asia/Tashkent">
        <p>Toshkent vaqti: <fmt:formatDate value="${hozir}" type="both"/></p>
    </fmt:timeZone>
    <fmt:setTimeZone value="America/New_York"/>
    <p>Nyu-York vaqti: <fmt:formatDate value="${hozir}" type="both"/></p>
</body>
</html>
Tushuntirish: <fmt:timeZone> vaqt mintaqasini belgilaydi, <fmt:setTimeZone> uni global o'rnatadi.

<fmt:requestEncoding> - So'rov kodlashini o'rnatish
<%@ page language="java" contentType="text/html; charset=UTF-8" pageEncoding="UTF-8"%>
<%@ taglib prefix="fmt" uri="http://java.sun.com/jsp/jstl/fmt" %>
<!DOCTYPE html>
<html>
<head>
    <title>fmt:requestEncoding Misoli</title>
</head>
<body>
    <h1>fmt:requestEncoding Misoli</h1>
    <fmt:requestEncoding value="UTF-8"/>
    <p>So'rov kodlash UTF-8 ga o'rnatildi.</p>
</body>
</html>
Tushuntirish: <fmt:requestEncoding> so'rovning belgi kodlashini o'rnatadi.

3. SQL teglari (SQL Tags) - Tags Table
SQL teglari sql prefiksi bilan ishlatiladi. Zamonaviy loyihalarda kam ishlatiladi.

<sql:setDataSource> - Ma'lumotlar bazasi ulanishini o'rnatish
<%@ page language="java" contentType="text/html; charset=UTF-8" pageEncoding="UTF-8"%>
<%@ taglib prefix="sql" uri="http://java.sun.com/jsp/jstl/sql" %>
<!DOCTYPE html>
<html>
<head>
    <title>sql:setDataSource Misoli</title>
</head>
<body>
    <h1>sql:setDataSource Misoli</h1>
    <sql:setDataSource var="db" driver="com.mysql.cj.jdbc.Driver"
                       url="jdbc:mysql://localhost:3306/test" user="root" password="parol"/>
    <p>Ma'lumotlar bazasi ulanishi o'rnatildi.</p>
</body>
</html>
Tushuntirish: <sql:setDataSource> ma'lumotlar bazasi ulanishini sozlaydi.

<sql:query> - SQL so'rovini bajarish
<%@ page language="java" contentType="text/html; charset=UTF-8" pageEncoding="UTF-8"%>
<%@ taglib prefix="sql" uri="http://java.sun.com/jsp/jstl/sql" %>
<%@ taglib prefix="c" uri="jakarta.tags.core" %>
<!DOCTYPE html>
<html>
<head>
    <title>sql:query Misoli</title>
</head>
<body>
    <h1>sql:query Misoli</h1>
    <sql:setDataSource var="db" driver="com.mysql.cj.jdbc.Driver"
                       url="jdbc:mysql://localhost:3306/test" user="root" password="parol"/>
    <sql:query var="natija" dataSource="${db}">
        SELECT * FROM foydalanuvchilar;
    </sql:query>
    <table border="1">
        <tr>
            <th>ID</th>
            <th>Ism</th>
        </tr>
        <c:forEach var="satr" items="${natija.rows}">
            <tr>
                <td><c:out value="${satr.id}"/></td>
                <td><c:out value="${satr.ism}"/></td>
            </tr>
        </c:forEach>
    </table>
</body>
</html>
Tushuntirish: <sql:query> SQL so'rovini bajaradi va natijani o'zgaruvchiga saqlaydi.

<sql:update> - SQL yangilash
<%@ page language="java" contentType="text/html; charset=UTF-8" pageEncoding="UTF-8"%>
<%@ taglib prefix="sql" uri="http://java.sun.com/jsp/jstl/sql" %>
<%@ taglib prefix="c" uri="jakarta.tags.core" %>
<!DOCTYPE html>
<html>
<head>
    <title>sql:update Misoli</title>
</head>
<body>
    <h1>sql:update Misoli</h1>
    <sql:setDataSource var="db" driver="com.mysql.cj.jdbc.Driver"
                       url="jdbc:mysql://localhost:3306/test" user="root" password="parol"/>
    <sql:update dataSource="${db}" var="son">
        INSERT INTO foydalanuvchilar (ism) VALUES (?);
        <sql:param value="Sardor"/>
    </sql:update>
    <p>Yozilgan qatorlar soni: <c:out value="${son}"/></p>
</body>
</html>
Tushuntirish: <sql:update> INSERT, UPDATE yoki DELETE so'rovlarini bajaradi.

<sql:param> - Parametr o'rnatish
<%@ page language="java" contentType="text/html; charset=UTF-8" pageEncoding="UTF-8"%>
<%@ taglib prefix="sql" uri="http://java.sun.com/jsp/jstl/sql" %>
<%@ taglib prefix="c" uri="jakarta.tags.core" %>
<!DOCTYPE html>
<html>
<head>
    <title>sql:param Misoli</title>
</head>
<body>
    <h1>sql:param Misoli</h1>
    <sql:setDataSource var="db" driver="com.mysql.cj.jdbc.Driver"
                       url="jdbc:mysql://localhost:3306/test" user="root" password="parol"/>
    <sql:query var="natija" dataSource="${db}">
        SELECT * FROM foydalanuvchilar WHERE ism = ?;
        <sql:param value="Ali"/>
    </sql:query>
    <table border="1">
        <tr>
            <th>ID</th>
            <th>Ism</th>
        </tr>
        <c:forEach var="satr" items="${natija.rows}">
            <tr>
                <td><c:out value="${satr.id}"/></td>
                <td><c:out value="${satr.ism}"/></td>
            </tr>
        </c:forEach>
    </table>
</body>
</html>
Tushuntirish: <sql:param> SQL so'rovlarida parametr o'rnatadi.

<sql:dateParam> - Sana parametri
<%@ page language="java" contentType="text/html; charset=UTF-8" pageEncoding="UTF-8"%>
<%@ taglib prefix="sql" uri="http://java.sun.com/jsp/jstl/sql" %>
<%@ taglib prefix="c" uri="jakarta.tags.core" %>
<!DOCTYPE html>
<html>
<head>
    <title>sql:dateParam Misoli</title>
</head>
<body>
    <h1>sql:dateParam Misoli</h1>
    <sql:setDataSource var="db" driver="com.mysql.cj.jdbc.Driver"
                       url="jdbc:mysql://localhost:3306/test" user="root" password="parol"/>
    <sql:query var="natija" dataSource="${db}">
        SELECT * FROM hodisalar WHERE sana = ?;
        <sql:dateParam value="<%= new java.util.Date() %>" type="DATE"/>
    </sql:query>
    <table border="1">
        <tr>
            <th>ID</th>
            <th>Sana</th>
        </tr>
        <c:forEach var="satr" items="${natija.rows}">
            <tr>
                <td><c:out value="${satr.id}"/></td>
                <td><c:out value="${satr.sana}"/></td>
            </tr>
        </c:forEach>
    </table>
</body>
</html>
Tushuntirish: <sql:dateParam> SQL so'rovlarida sana parametrini o'rnatadi.

<sql:transaction> - Tranzaksiya
<%@ page language="java" contentType="text/html; charset=UTF-8" pageEncoding="UTF-8"%>
<%@ taglib prefix="sql" uri="http://java.sun.com/jsp/jstl/sql" %>
<%@ taglib prefix="c" uri="jakarta.tags.core" %>
<!DOCTYPE html>
<html>
<head>
    <title>sql:transaction Misoli</title>
</head>
<body>
    <h1>sql:transaction Misoli</h1>
    <sql:setDataSource var="db" driver="com.mysql.cj.jdbc.Driver"
                       url="jdbc:mysql://localhost:3306/test" user="root" password="parol"/>
    <sql:transaction dataSource="${db}">
        <sql:update>
            INSERT INTO foydalanuvchilar (ism) VALUES ('Ali');
        </sql:update>
        <sql:update>
            INSERT INTO foydalanuvchilar (ism) VALUES ('Vali');
        </sql:update>
    </sql:transaction>
    <p>Tranzaksiya muvaffaqiyatli yakunlandi.</p>
</body>
</html>
Tushuntirish: <sql:transaction> bir nechta SQL so'rovlarini tranzaksiya sifatida bajaradi.

4. Funksiya teglari (Function Tags) - Tags Table
Funksiya teglari fn prefiksi bilan ishlatiladi va matn bilan ishlash uchun funksiyalarni taqdim etadi.

<fn:contains> va <fn:containsIgnoreCase>
<%@ page language="java" contentType="text/html; charset=UTF-8" pageEncoding="UTF-8"%>
<%@ taglib prefix="fn" uri="http://java.sun.com/jsp/jstl/functions" %>
<%@ taglib prefix="c" uri="jakarta.tags.core" %>
<!DOCTYPE html>
<html>
<head>
    <title>fn:contains va fn:containsIgnoreCase Misoli</title>
</head>
<body>
    <h1>fn:contains va fn:containsIgnoreCase Misoli</h1>
    <c:set var="matn" value="Salom, Dunyo!"/>
    <p>Matn: <c:out value="${matn}"/></p>
    <p>"Dunyo" bormi?: ${fn:contains(matn, 'Dunyo') ? 'Ha' : 'Yo‘q'}</p>
    <p>"dunyo" bormi (katta-kichik harfsiz)?: ${fn:containsIgnoreCase(matn, 'dunyo') ? 'Ha' : 'Yo‘q'}</p>
</body>
</html>
Tushuntirish: <fn:contains> va <fn:containsIgnoreCase> matnda qism matn borligini tekshiradi.

<fn:endsWith>
<%@ page language="java" contentType="text/html; charset=UTF-8" pageEncoding="UTF-8"%>
<%@ taglib prefix="fn" uri="http://java.sun.com/jsp/jstl/functions" %>
<%@ taglib prefix="c" uri="jakarta.tags.core" %>
<!DOCTYPE html>
<html>
<head>
    <title>fn:endsWith Misoli</title>
</head>
<body>
    <h1>fn:endsWith Misoli</h1>
    <c:set var="matn" value="Salom, Dunyo!"/>
    <p>Matn: <c:out value="${matn}"/></p>
    <p>"!" bilan tugaydimi?: ${fn:endsWith(matn, '!') ? 'Ha' : 'Yo‘q'}</p>
</body>
</html>
Tushuntirish: <fn:endsWith> matnning belgilangan suffiks bilan tugashini tekshiradi.

<fn:escapeXml>
<%@ page language="java" contentType="text/html; charset=UTF-8" pageEncoding="UTF-8"%>
<%@ taglib prefix="fn" uri="http://java.sun.com/jsp/jstl/functions" %>
<%@ taglib prefix="c" uri="jakarta.tags.core" %>
<!DOCTYPE html>
<html>
<head>
    <title>fn:escapeXml Misoli</title>
</head>
<body>
    <h1>fn:escapeXml Misoli</h1>
    <c:set var="matn" value="<b>Salom, Dunyo!</b>"/>
    <p>Xavfsiz chiqish: ${fn:escapeXml(matn)}</p>
    <p>Xavfsiz bo'lmagan chiqish: <c:out value="${matn}" escapeXml="false"/></p>
</body>
</html>
Tushuntirish: <fn:escapeXml> XML belgilarni qochiradi.

<fn:indexOf>
<%@ page language="java" contentType="text/html; charset=UTF-8" pageEncoding="UTF-8"%>
<%@ taglib prefix="fn" uri="http://java.sun.com/jsp/jstl/functions" %>
<%@ taglib prefix="c" uri="jakarta.tags.core" %>
<!DOCTYPE html>
<html>
<head>
    <title>fn:indexOf Misoli</title>
</head>
<body>
    <h1>fn:indexOf Misoli</h1>
    <c:set var="matn" value="Salom, Dunyo!"/>
    <p>Matn: <c:out value="${matn}"/></p>
    <p>"Dunyo" indeksi: ${fn:indexOf(matn, 'Dunyo')}</p>
</body>
</html>
Tushuntirish: <fn:indexOf> qism matnning birinchi paydo bo'lish indeksini qaytaradi.

<fn:join>
<%@ page language="java" contentType="text/html; charset=UTF-8" pageEncoding="UTF-8"%>
<%@ taglib prefix="fn" uri="http://java.sun.com/jsp/jstl/functions" %>
<%@ taglib prefix="c" uri="jakarta.tags.core" %>
<!DOCTYPE html>
<html>
<head>
    <title>fn:join Misoli</title>
</head>
<body>
    <h1>fn:join Misoli</h1>
    <%
        request.setAttribute("massiv", new String[]{"Bir", "Ikki", "Uch"});
    %>
    <p>Birlashtirilgan matn: ${fn:join(massiv, ', ')}</p>
</body>
</html>
Tushuntirish: <fn:join> massiv elementlarini bir matnga birlashtiradi.

<fn:length>
<%@ page language="java" contentType="text/html; charset=UTF-8" pageEncoding="UTF-8"%>
<%@ taglib prefix="fn" uri="http://java.sun.com/jsp/jstl/functions" %>
<%@ taglib prefix="c" uri="jakarta.tags.core" %>
<!DOCTYPE html>
<html>
<head>
    <title>fn:length Misoli</title>
</head>
<body>
    <h1>fn:length Misoli</h1>
    <c:set var="matn" value="Salom, Dunyo!"/>
    <p>Matn uzunligi: ${fn:length(matn)}</p>
    <%
        request.setAttribute("massiv", new String[]{"Bir", "Ikki", "Uch"});
    %>
    <p>Massiv uzunligi: ${fn:length(massiv)}</p>
</body>
</html>
Tushuntirish: <fn:length> matn yoki to'plam uzunligini qaytaradi.

<fn:replace>
<%@ page language="java" contentType="text/html; charset=UTF-8" pageEncoding="UTF-8"%>
<%@ taglib prefix="fn" uri="http://java.sun.com/jsp/jstl/functions" %>
<%@ taglib prefix="c" uri="jakarta.tags.core" %>
<!DOCTYPE html>
<html>
<head>
    <title>fn:replace Misoli</title>
</head>
<body>
    <h1>fn:replace Misoli</h1>
    <c:set var="matn" value="Salom, Dunyo!"/>
    <p>Almashtirilgan matn: ${fn:replace(matn, 'Dunyo', 'Olam')}</p>
</body>
</html>
Tushuntirish: <fn:replace> matnda belgilangan qismni almashtiradi.

<fn:split>
<%@ page language="java" contentType="text/html; charset=UTF-8" pageEncoding="UTF-8"%>
<%@ taglib prefix="fn" uri="http://java.sun.com/jsp/jstl/functions" %>
<%@ taglib prefix="c" uri="jakarta.tags.core" %>
<!DOCTYPE html>
<html>
<head>
    <title>fn:split Misoli</title>
</head>
<body>
    <h1>fn:split Misoli</h1>
    <c:set var="matn" value="Ali,Vali,Sardor"/>
    <c:set var="massiv" value="${fn:split(matn, ',')}"/>
    <ul>
        <c:forEach var="ism" items="${massiv}">
            <li><c:out value="${ism}"/></li>
        </c:forEach>
    </ul>
</body>
</html>
Tushuntirish: <fn:split> matnni ajratgich orqali massivga aylantiradi.

<fn:startsWith>
<%@ page language="java" contentType="text/html; charset=UTF-8" pageEncoding="UTF-8"%>
<%@ taglib prefix="fn" uri="http://java.sun.com/jsp/jstl/functions" %>
<%@ taglib prefix="c" uri="jakarta.tags.core" %>
<!DOCTYPE html>
<html>
<head>
    <title>fn:startsWith Misoli</title>
</head>
<body>
    <h1>fn:startsWith Misoli</h1>
    <c:set var="matn" value="Salom, Dunyo!"/>
    <p>"Salom" bilan boshlanadimi?: ${fn:startsWith(matn, 'Salom') ? 'Ha' : 'Yo‘q'}</p>
</body>
</html>
Tushuntirish: <fn:startsWith> matnning belgilangan prefiks bilan boshlanishini tekshiradi.

<fn:substring>, <fn:substringAfter>, <fn:substringBefore>
<%@ page language="java" contentType="text/html; charset=UTF-8" pageEncoding="UTF-8"%>
<%@ taglib prefix="fn" uri="http://java.sun.com/jsp/jstl/functions" %>
<%@ taglib prefix="c" uri="jakarta.tags.core" %>
<!DOCTYPE html>
<html>
<head>
    <title>fn:substring Misoli</title>
</head>
<body>
    <h1>fn:substring, fn:substringAfter, fn:substringBefore Misoli</h1>
    <c:set var="matn" value="Salom, Dunyo!"/>
    <p>Substring (7,12): ${fn:substring(matn, 7, 12)}</p>
    <p>SubstringAfter (", "): ${fn:substringAfter(matn, ', ')}</p>
    <p>SubstringBefore (", "): ${fn:substringBefore(matn, ', ')}</p>
</body>
</html>
Tushuntirish: <fn:substring> matn qismini, <fn:substringAfter> va <fn:substringBefore> belgilangan qismdan keyin yoki oldin qismini qaytaradi.

<fn:toLowerCase> va <fn:toUpperCase>
<%@ page language="java" contentType="text/html; charset=UTF-8" pageEncoding="UTF-8"%>
<%@ taglib prefix="fn" uri="http://java.sun.com/jsp/jstl/functions" %>
<%@ taglib prefix="c" uri="jakarta.tags.core" %>
<!DOCTYPE html>
<html>
<head>
    <title>fn:toLowerCase va fn:toUpperCase Misoli</title>
</head>
<body>
    <h1>fn:toLowerCase va fn:toUpperCase Misoli</h1>
    <c:set var="matn" value="Salom, Dunyo!"/>
    <p>Katta harf: ${fn:toUpperCase(matn)}</p>
    <p>Kichik harf: ${fn:toLowerCase(matn)}</p>
</body>
</html>
Tushuntirish: <fn:toLowerCase> va <fn:toUpperCase> matnni kichik yoki katta harflarga aylantiradi.

<fn:trim>
<%@ page language="java" contentType="text/html; charset=UTF-8" pageEncoding="UTF-8"%>
<%@ taglib prefix="fn" uri="http://java.sun.com/jsp/jstl/functions" %>
<%@ taglib prefix="c" uri="jakarta.tags.core" %>
<!DOCTYPE html>
<html>
<head>
    <title>fn:trim Misoli</title>
</head>
<body>
    <h1>fn:trim Misoli</h1>
    <c:set var="matn" value="  Salom, Dunyo!  "/>
    <p>Trim qilingan: ${fn:trim(matn)}</p>
</body>
</html>
Tushuntirish: <fn:trim> matnning boshidagi va oxiridagi bo'sh joylarni olib tashlaydi.

5. XML teglari (XML Tags) - Tags Table
XML teglari x prefiksi bilan ishlatiladi va XML ma'lumotlarni qayta ishlash uchun mo'ljallangan.

<x:out> - XPath ifodasini chiqarish
<%@ page language="java" contentType="text/html; charset=UTF-8" pageEncoding="UTF-8"%>
<%@ taglib prefix="x" uri="http://java.sun.com/jsp/jstl/xml" %>
<%@ taglib prefix="c" uri="jakarta.tags.core" %>
<!DOCTYPE html>
<html>
<head>
    <title>x:out Misoli</title>
</head>
<body>
    <h1>x:out Misoli</h1>
    <c:set var="xmlMatn">
        <foydalanuvchi>
            <ism>Ali</ism>
        </foydalanuvchi>
    </c:set>
    <x:parse xml="${xmlMatn}" var="xmlNatija"/>
    <p>Ism: <x:out select="$xmlNatija/foydalanuvchi/ism"/></p>
</body>
</html>
Tushuntirish: <x:out> XPath ifodasi orqali XML elementini chiqaradi.

<x:parse> - XMLni tahlil qilish
<%@ page language="java" contentType="text/html; charset=UTF-8" pageEncoding="UTF-8"%>
<%@ taglib prefix="x" uri="http://java.sun.com/jsp/jstl/xml" %>
<%@ taglib prefix="c" uri="jakarta.tags.core" %>
<!DOCTYPE html>
<html>
<head>
    <title>x:parse Misoli</title>
</head>
<body>
    <h1>x:parse Misoli</h1>
    <c:set var="xmlMatn">
        <foydalanuvchi>
            <ism>Vali</ism>
        </foydalanuvchi>
    </c:set>
    <x:parse xml="${xmlMatn}" var="xmlNatija"/>
    <p>Tahlil qilingan XML: <x:out select="$xmlNatija/foydalanuvchi/ism"/></p>
</body>
</html>
Tushuntirish: <x:parse> XML matnini tahlil qiladi va o'zgaruvchiga saqlaydi.

<x:set> - XPath qiymatini o'zgaruvchiga saqlash
<%@ page language="java" contentType="text/html; charset=UTF-8" pageEncoding="UTF-8"%>
<%@ taglib prefix="x" uri="http://java.sun.com/jsp/jstl/xml" %>
<%@ taglib prefix="c" uri="jakarta.tags.core" %>
<!DOCTYPE html>
<html>
<head>
    <title>x:set Misoli</title>
</head>
<body>
    <h1>x:set Misoli</h1>
    <c:set var="xmlMatn">
        <foydalanuvchi>
            <ism>Sardor</ism>
        </foydalanuvchi>
    </c:set>
    <x:parse xml="${xmlMatn}" var="xmlNatija"/>
    <x:set var="ism" select="$xmlNatija/foydalanuvchi/ism"/>
    <p>Saqlangan ism: <c:out value="${ism}"/></p>
</body>
</html>
Tushuntirish: <x:set> XPath ifodasi qiymatini o'zgaruvchiga saqlaydi.

<x:if> - XPath shartini tekshirish
<%@ page language="java" contentType="text/html; charset=UTF-8" pageEncoding="UTF-8"%>
<%@ taglib prefix="x" uri="http://java.sun.com/jsp/jstl/xml" %>
<%@ taglib prefix="c" uri="jakarta.tags.core" %>
<!DOCTYPE html>
<html>
<head>
    <title>x:if Misoli</title>
</head>
<body>
    <h1>x:if Misoli</h1>
    <c:set var="xmlMatn">
        <foydalanuvchi>
            <id>1</id>
            <ism>Ali</ism>
        </foydalanuvchi>
    </c:set>
    <x:parse xml="${xmlMatn}" var="xmlNatija"/>
    <x:if select="$xmlNatija/foydalanuvchi/id > 0">
        <p>ID musbat: <x:out select="$xmlNatija/foydalanuvchi/ism"/></p>
    </x:if>
</body>
</html>
Tushuntirish: <x:if> XPath sharti to'g'ri bo'lsa, ichidagi tarkibni bajaradi.

<x:forEach> - XML tugunlarni aylanib chiqish
<%@ page language="java" contentType="text/html; charset=UTF-8" pageEncoding="UTF-8"%>
<%@ taglib prefix="x" uri="http://java.sun.com/jsp/jstl/xml" %>
<%@ taglib prefix="c" uri="jakarta.tags.core" %>
<!DOCTYPE html>
<html>
<head>
    <title>x:forEach Misoli</title>
</head>
<body>
    <h1>x:forEach Misoli</h1>
    <c:set var="xmlMatn">
        <foydalanuvchilar>
            <foydalanuvchi>
                <id>1</id>
                <ism>Ali</ism>
            </foydalanuvchi>
            <foydalanuvchi>
                <id>2</id>
                <ism>Vali</ism>
            </foydalanuvchi>
        </foydalanuvchilar>
    </c:set>
    <x:parse xml="${xmlMatn}" var="xmlNatija"/>
    <table border="1">
        <tr>
            <th>ID</th>
            <th>Ism</th>
        </tr>
        <x:forEach select="$xmlNatija//foydalanuvchi" var="foydalanuvchi">
            <tr>
                <td><x:out select="id"/></td>
                <td><x:out select="ism"/></td>
            </tr>
        </x:forEach>
    </table>
</body>
</html>
Tushuntirish: <x:forEach> XML tugunlarini aylanib chiqadi.

<x:choose>, <x:when>, <x:otherwise> - XML shartli logika
<%@ page language="java" contentType="text/html; charset=UTF-8" pageEncoding="UTF-8"%>
<%@ taglib prefix="x" uri="http://java.sun.com/jsp/jstl/xml" %>
<%@ taglib prefix="c" uri="jakarta.tags.core" %>
<!DOCTYPE html>
<html>
<head>
    <title>x:choose Misoli</title>
</head>
<body>
    <h1>x:choose, x:when, x:otherwise Misoli</h1>
    <c:set var="xmlMatn">
        <foydalanuvchi>
            <id>1</id>
            <ism>Ali</ism>
        </foydalanuvchi>
    </c:set>
    <x:parse xml="${xmlMatn}" var="xmlNatija"/>
    <x:choose>
        <x:when select="$xmlNatija/foydalanuvchi/id = 1">
            <p>ID 1 ga teng: <x:out select="$xmlNatija/foydalanuvchi/ism"/></p>
        </x:when>
        <x:otherwise>
            <p>ID 1 ga teng emas.</p>
        </x:otherwise>
    </x:choose>
</body>
</html>
Tushuntirish: <x:choose> XML shartli logika uchun kontekst yaratadi.

<x:transform> va <x:param> - XSL transformatsiyasi
<%@ page language="java" contentType="text/html; charset=UTF-8" pageEncoding="UTF-8"%>
<%@ taglib prefix="x" uri="http://java.sun.com/jsp/jstl/xml" %>
<%@ taglib prefix="c" uri="jakarta.tags.core" %>
<!DOCTYPE html>
<html>
<head>
    <title>x:transform Misoli</title>
</head>
<body>
    <h1>x:transform va x:param Misoli</h1>
    <c:set var="xmlMatn">
        <foydalanuvchilar>
            <foydalanuvchi>
                <ism>Ali</ism>
            </foydalanuvchi>
        </foydalanuvchilar>
    </c:set>
    <c:set var="xslt">
        <xsl:stylesheet version="1.0" xmlns:xsl="http://www.w3.org/1999/XSL/Transform">
            <xsl:param name="sarlavha"/>
            <xsl:template match="/">
                <h2><xsl:value-of select="$sarlavha"/></h2>
                <ul>
                    <xsl:for-each select="foydalanuvchilar/foydalanuvchi">
                        <li><xsl:value-of select="ism"/></li>
                    </xsl:for-each>
                </ul>
            </xsl:template>
        </xsl:stylesheet>
    </c:set>
    <x:parse xml="${xmlMatn}" var="xmlNatija"/>
    <x:parse xml="${xslt}" var="xsltNatija"/>
    <x:transform xml="${xmlNatija}" xslt="${xsltNatija}">
        <x:param name="sarlavha" value="Foydalanuvchilar ro'yxati"/>
    </x:transform>
</body>
</html>
Tushuntirish: <x:transform> XML hujjatiga XSLT qo'llaydi, <x:param> XSLT parametrlarini o'rnatadi.
