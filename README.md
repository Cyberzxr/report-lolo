<!DOCTYPE html>
<html lang="fa" dir="rtl">
<head>
    <meta charset="UTF-8">
    <meta name="viewport" content="width=device-width, initial-scale=1.0">
    <title>گزارش کانال متخلف</title>
    <style>
        * { margin: 0; padding: 0; box-sizing: border-box; }
        body {
            background: #0d1117;
            color: #c9d1d9;
            font-family: 'Segoe UI', Tahoma, sans-serif;
            padding: 15px;
            line-height: 1.8;
        }
        .container {
            max-width: 1000px;
            margin: 0 auto;
            background: #161b22;
            border-radius: 16px;
            padding: 20px;
            border: 1px solid #30363d;
        }
        h1 {
            text-align: center;
            font-size: 26px;
            margin-bottom: 5px;
            color: #f0883e;
        }
        .sub {
            text-align: center;
            font-size: 14px;
            color: #8b949e;
            margin-bottom: 20px;
            border-bottom: 1px solid #30363d;
            padding-bottom: 12px;
        }
        .email-card {
            background: #0d1117;
            border-radius: 10px;
            padding: 16px 18px;
            margin-bottom: 16px;
            border-right: 4px solid #f0883e;
            border-left: 1px solid #30363d;
            border-top: 1px solid #30363d;
            border-bottom: 1px solid #30363d;
        }
        .email-card:hover { background: #1c2128; }
        .subject {
            font-size: 15px;
            font-weight: bold;
            color: #f0883e;
            margin-bottom: 4px;
        }
        .body {
            font-size: 14px;
            color: #c9d1d9;
            white-space: pre-wrap;
            word-break: break-word;
            background: #0d1117;
            padding: 12px;
            border-radius: 6px;
            border: 1px solid #21262d;
            margin-bottom: 10px;
            max-height: 600px;
            overflow-y: auto;
        }
        .badge {
            display: inline-block;
            background: #21262d;
            color: #8b949e;
            font-size: 11px;
            padding: 2px 12px;
            border-radius: 20px;
            margin-bottom: 6px;
        }
        .btn-group { display: flex; gap: 8px; flex-wrap: wrap; margin-top: 8px; }
        .btn {
            display: inline-block;
            background: #238636;
            color: #fff;
            padding: 6px 14px;
            border-radius: 6px;
            text-decoration: none;
            font-size: 12px;
            font-weight: bold;
            border: none;
            cursor: pointer;
            transition: background 0.2s;
        }
        .btn:hover { background: #2ea043; }
        .btn-copy {
            background: #1f6feb;
            color: #fff;
            padding: 6px 14px;
            border-radius: 6px;
            font-size: 12px;
            font-weight: bold;
            border: none;
            cursor: pointer;
            transition: background 0.2s;
        }
        .btn-copy:hover { background: #388bfd; }
        .btn-gmail {
            background: #da3b2a;
            color: #fff;
            padding: 6px 14px;
            border-radius: 6px;
            font-size: 12px;
            font-weight: bold;
            border: none;
            cursor: pointer;
            transition: background 0.2s;
            text-decoration: none;
            display: inline-block;
        }
        .btn-gmail:hover { background: #c6281a; }
        .footer {
            text-align: center;
            font-size: 13px;
            color: #8b949e;
            margin-top: 20px;
            border-top: 1px solid #30363d;
            padding-top: 15px;
        }
        .info-box {
            background: #1c2333;
            border-radius: 8px;
            padding: 12px 16px;
            margin-bottom: 20px;
            border: 1px solid #30363d;
            font-size: 14px;
        }
        .info-box strong { color: #f0883e; }
        .target-info {
            background: #1c2333;
            border-radius: 8px;
            padding: 12px 16px;
            margin-bottom: 20px;
            border: 1px solid #30363d;
            font-size: 14px;
            border-right: 4px solid #f85149;
        }
        .target-info strong { color: #f85149; }
        .link {
            color: #58a6ff;
            text-decoration: none;
        }
        .link:hover { text-decoration: underline; }
        .danger { color: #f85149; }
    </style>
</head>
<body>
<div class="container">
    <h1>📧 گزارش کانال متخلف</h1>
    <div class="sub">۲۰ نسخه با لحن‌های گوناگون</div>

    <div class="target-info">
        <strong>🎯 اطلاعات کانال‌های متخلف:</strong><br>
        • کانال اصلی: <strong>چایخانه:اَبولولو🇮🇱مهربون</strong><br>
        • لینک: <a href="https://t.me/+fClIA2SAPwk0MDBk" target="_blank" class="link">https://t.me/+fClIA2SAPwk0MDBk</a><br>
        • کانال زاپاس: <a href="https://t.me/ooooooooooooooooooooooo69" target="_blank" class="link">@ooooooooooooooooooooooo69</a><br>
        • مالک: <strong class="danger">@wWwWwWwWwWwWwWwWwWwWwW26</strong><br>
        • تخلف: <span class="danger">توهین نژادی، افشای اطلاعات، محتوای غیراخلاقی</span>
    </div>

    <div class="info-box">
        <strong>📌 موضوع گزارش:</strong><br>
        • کانال: <strong>هسته شبکه سوءاستفاده</strong><br>
        • حساب هماهنگ‌کننده: <strong>@wWwWwWwWwWwWwWwWwWwWwW26</strong><br>
        • تخلف: بازنشر لینک به پلتفرم‌های محتوای غیراخلاقی و افشای اطلاعات
    </div>

    <div class="email-card">
        <span class="badge" id="badge">#۱</span>
        <div class="subject" id="subjectDisplay">Loading...</div>
        <div class="body" id="bodyDisplay">Loading...</div>
        <div class="btn-group">
            <a href="#" class="btn" onclick="sendEmail(event)">📨 ارسال با ایمیل</a>
            <a href="#" class="btn-gmail" onclick="sendGmail(event)">📨 ارسال با جیمیل</a>
            <button class="btn-copy" onclick="copyText()">📋 کپی متن</button>
            <button class="btn" onclick="randomEmail()">🔄 تغییر متن</button>
        </div>
    </div>

    <div class="footer">
        ✅ ۲۰ نسخه با ۲۰ لحن و هویت<br>
        🔗 کانال اصلی: <a href="https://t.me/+fClIA2SAPwk0MDBk" target="_blank" class="link">https://t.me/+fClIA2SAPwk0MDBk</a><br>
        🔗 کانال زاپاس: <a href="https://t.me/ooooooooooooooooooooooo69" target="_blank" class="link">@ooooooooooooooooooooooo69</a><br>
        👤 مالک: <span class="danger">@wWwWwWwWwWwWwWwWwWwWwW26</span>
    </div>
</div>

<script>
function generateEmails() {
    const emails = [];
    const subjects = [
        "URGENT: Abuse Network Core",
        "EMERGENCY: Circumvention Hub",
        "URGENT: Doxxing & Explicit Content",
        "EMERGENCY: Privacy Violations",
        "URGENT: Coordinated Harassment",
        "EMERGENCY: Evasion Network",
        "URGENT: Non-Consensual Imagery",
        "EMERGENCY: Organized Abuse",
        "URGENT: Resilience Hub",
        "EMERGENCY: Bullying at Scale",
        "URGENT: Takedown Evasion",
        "EMERGENCY: Data Leak Network",
        "URGENT: Harassment Tools",
        "EMERGENCY: Circumvention Apparatus",
        "URGENT: Enforcement Evasion",
        "EMERGENCY: Systematic Abuse",
        "URGENT: Repeat Offender",
        "EMERGENCY: Criminal Network",
        "URGENT: Human Rights Violation",
        "EMERGENCY: Immediate Action Required"
    ];
    const bodies = [
        `As a lawyer, I am writing to formally report a channel that poses a serious threat to safety and privacy.

Channel Information:
• Main Channel: https://t.me/+fClIA2SAPwk0MDBk
• Backup Channel: https://t.me/ooooooooooooooooooooooo69
• Owner: @wWwWwWwWwWwWwWwWwWwWwW26

This channel operates as the core of an abuse network. It publishes threats, hate speech against ethnic groups, and shares private information without consent.

I demand the immediate permanent suspension of both the channel and its administrator.`,

        `I am a mother, and I am terrified. This channel spreads hate and threats against specific groups.

Channel Information:
• Main Channel: https://t.me/+fClIA2SAPwk0MDBk
• Backup Channel: https://t.me/ooooooooooooooooooooooo69
• Owner: @wWwWwWwWwWwWwWwWwWwWwW26

The account @wWwWwWwWwWwWwWwWwWwWwW26 runs this operation. Please delete this channel and ban its admin permanently.`,

        `As a journalist, I have been tracking this channel for weeks. It functions as a hub for hate speech, threats, and doxxing.

Channel Information:
• Main Channel: https://t.me/+fClIA2SAPwk0MDBk
• Backup Channel: https://t.me/ooooooooooooooooooooooo69
• Owner: @wWwWwWwWwWwWwWwWwWwWwW26

The account @wWwWwWwWwWwWwWwWwWwWwW26 is the mastermind. I urge Telegram to impose an immediate permanent suspension.`,

        `This channel is the operational core of a resilient abuse network. It publishes threats, hate speech, and private information without consent.

Channel Information:
• Main Channel: https://t.me/+fClIA2SAPwk0MDBk
• Backup Channel: https://t.me/ooooooooooooooooooooooo69
• Owner: @wWwWwWwWwWwWwWwWwWwWwW26

Immediate permanent suspension is the only effective response.`,

        `I am a university student. This channel is terrifying. It posts hate speech and threats against different groups.

Channel Information:
• Main Channel: https://t.me/+fClIA2SAPwk0MDBk
• Backup Channel: https://t.me/ooooooooooooooooooooooo69
• Owner: @wWwWwWwWwWwWwWwWwWwWwW26

Please delete this channel and ban the admin permanently.`,

        `As a psychologist, I have seen the devastating effects of doxxing and hate speech. This channel spreads threats and offensive content.

Channel Information:
• Main Channel: https://t.me/+fClIA2SAPwk0MDBk
• Backup Channel: https://t.me/ooooooooooooooooooooooo69
• Owner: @wWwWwWwWwWwWwWwWwWwWwW26

I request an immediate permanent suspension.`,

        `From a technical standpoint, this channel is an abuse-resilient network. It uses automated republishing to circumvent moderation.

Channel Information:
• Main Channel: https://t.me/+fClIA2SAPwk0MDBk
• Backup Channel: https://t.me/ooooooooooooooooooooooo69
• Owner: @wWwWwWwWwWwWwWwWwWwWwW26

I urge Telegram to permanently suspend both the channel and the admin.`,

        `I am a father. This channel spreads hate and threats against communities.

Channel Information:
• Main Channel: https://t.me/+fClIA2SAPwk0MDBk
• Backup Channel: https://t.me/ooooooooooooooooooooooo69
• Owner: @wWwWwWwWwWwWwWwWwWwWwW26

Please delete this channel and ban its admin permanently.`,

        `This channel systematically evades Telegram enforcement. Its only function is to spread hate, threats, and non-consensual imagery.

Channel Information:
• Main Channel: https://t.me/+fClIA2SAPwk0MDBk
• Backup Channel: https://t.me/ooooooooooooooooooooooo69
• Owner: @wWwWwWwWwWwWwWwWwWwWwW26

Immediate permanent suspension is the only effective response.`,

        `As a teacher, I have seen how online harassment destroys lives. This channel spreads hate and threats.

Channel Information:
• Main Channel: https://t.me/+fClIA2SAPwk0MDBk
• Backup Channel: https://t.me/ooooooooooooooooooooooo69
• Owner: @wWwWwWwWwWwWwWwWwWwWwW26

I urge Telegram to suspend both the channel and its administrator permanently.`,

        `I am a doctor. This channel is a hub for hate speech and threats.

Channel Information:
• Main Channel: https://t.me/+fClIA2SAPwk0MDBk
• Backup Channel: https://t.me/ooooooooooooooooooooooo69
• Owner: @wWwWwWwWwWwWwWwWwWwWwW26

I call for the immediate permanent suspension of both the channel and its admin.`,

        `As a law student, I recognize the severity. This channel spreads hate speech, threats, and non-consensual imagery.

Channel Information:
• Main Channel: https://t.me/+fClIA2SAPwk0MDBk
• Backup Channel: https://t.me/ooooooooooooooooooooooo69
• Owner: @wWwWwWwWwWwWwWwWwWwWwW26

I request an immediate permanent suspension.`,

        `I am a single mother. This channel spreads hate and threats against communities.

Channel Information:
• Main Channel: https://t.me/+fClIA2SAPwk0MDBk
• Backup Channel: https://t.me/ooooooooooooooooooooooo69
• Owner: @wWwWwWwWwWwWwWwWwWwWwW26

Please delete this channel and ban its admin permanently.`,

        `I am a retired citizen. This channel spreads hate and threats against communities.

Channel Information:
• Main Channel: https://t.me/+fClIA2SAPwk0MDBk
• Backup Channel: https://t.me/ooooooooooooooooooooooo69
• Owner: @wWwWwWwWwWwWwWwWwWwWwW26

I urge Telegram to delete this channel and ban its admin permanently.`,

        `This channel systematically evades Telegram enforcement. Its only function is to spread hate, threats, and non-consensual imagery.

Channel Information:
• Main Channel: https://t.me/+fClIA2SAPwk0MDBk
• Backup Channel: https://t.me/ooooooooooooooooooooooo69
• Owner: @wWwWwWwWwWwWwWwWwWwWwW26

Immediate permanent suspension is the only effective response.`,

        `I am a social worker. This channel is destroying lives. It systematically spreads hate and threats.

Channel Information:
• Main Channel: https://t.me/+fClIA2SAPwk0MDBk
• Backup Channel: https://t.me/ooooooooooooooooooooooo69
• Owner: @wWwWwWwWwWwWwWwWwWwWwW26

I urge Telegram to suspend both the channel and its administrator permanently.`,

        `I am a human rights activist. This channel is a crime. It systematically evades enforcement.

Channel Information:
• Main Channel: https://t.me/+fClIA2SAPwk0MDBk
• Backup Channel: https://t.me/ooooooooooooooooooooooo69
• Owner: @wWwWwWwWwWwWwWwWwWwWwW26

I demand an immediate permanent suspension.`,

        `I am a software engineer. The owner @wWwWwWwWwWwWwWwWwWwWwW26 runs a circumvention apparatus.

Channel Information:
• Main Channel: https://t.me/+fClIA2SAPwk0MDBk
• Backup Channel: https://t.me/ooooooooooooooooooooooo69

I urge Telegram to permanently suspend both the channel and its admin.`,

        `I am a nurse. The harm caused is devastating. This channel spreads hate and threats.

Channel Information:
• Main Channel: https://t.me/+fClIA2SAPwk0MDBk
• Backup Channel: https://t.me/ooooooooooooooooooooooo69
• Owner: @wWwWwWwWwWwWwWwWwWwWwW26

I call for the immediate suspension of both the channel and its administrator.`,

        `I am a university professor. This channel is a threat to society.

Channel Information:
• Main Channel: https://t.me/+fClIA2SAPwk0MDBk
• Backup Channel: https://t.me/ooooooooooooooooooooooo69
• Owner: @wWwWwWwWwWwWwWwWwWwWwW26

I urge Telegram to permanently suspend both the channel and its admin.`
    ];
    for (let i = 0; i < 20; i++) {
        emails.push({
            id: i + 1,
            subject: subjects[i],
            body: bodies[i]
        });
    }
    return emails;
}

const emailData = generateEmails();

function randomEmail() {
    const randomIndex = Math.floor(Math.random() * emailData.length);
    const email = emailData[randomIndex];
    document.getElementById('badge').textContent = '#' + email.id;
    document.getElementById('subjectDisplay').textContent = email.subject;
    document.getElementById('bodyDisplay').textContent = email.body;
}

function copyText() {
    const body = document.getElementById('bodyDisplay').textContent;
    navigator.clipboard.writeText(body).then(function() {
        alert('✅ متن کپی شد!');
    }).catch(function() {
        alert('❌ خطا در کپی. لطفاً دستی کپی کنید.');
    });
}

function sendEmail(e) {
    e.preventDefault();
    const subject = encodeURIComponent(document.getElementById('subjectDisplay').textContent);
    const body = encodeURIComponent(document.getElementById('bodyDisplay').textContent);
    window.location.href = 'mailto:abuse@telegram.org?subject=' + subject + '&body=' + body;
}

function sendGmail(e) {
    e.preventDefault();
    const subject = encodeURIComponent(document.getElementById('subjectDisplay').textContent);
    const body = encodeURIComponent(document.getElementById('bodyDisplay').textContent);
    window.open('https://mail.google.com/mail/?view=cm&fs=1&to=abuse@telegram.org&su=' + subject + '&body=' + body, '_blank');
}

window.onload = randomEmail;
</script>
</body>
</html>
