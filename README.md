# bal-sanskar-shibir
// Save this file as: app/page.jsx (for Vercel / Next.js deployment) export default function BalSanskarShibirForm() { const handleSubmit = (e) => { e.preventDefault(); const form = new FormData(e.target); const message = नवीन नोंदणी:%0Aनाव: ${form.get('name')}%0Aवय: ${form.get('age')}%0Aलिंग: ${form.get('gender')}%0Aफोन: ${form.get('phone')}%0Aपत्ता: ${form.get('address')}; window.open(https://wa.me/919405275826?text=${message}, '_blank'); };

return ( <div className="min-h-screen bg-orange-50 flex items-center justify-center p-4"> <div className="w-full max-w-2xl bg-white rounded-3xl shadow-xl p-8 border border-orange-200"> <h1 className="text-3xl font-bold text-center text-orange-700 mb-2"> महानुभाव पंथ बाल संस्कार शिबीर </h1> <p className="text-center text-gray-700 mb-6"> श्री कृष्ण ज्ञानमंदिर, तपश्चर्या गुरुकुल महानुभाव आश्रम ट्रस्ट (रजि) रोझे, खलाने </p>

<div className="border-2 border-dashed border-gray-300 rounded-2xl h-40 flex items-center justify-center text-gray-400 mb-6">
      Banner / Photo Space
    </div>

    <form className="space-y-4" onSubmit={handleSubmit}>
      <input name="name" className="w-full p-3 border rounded-xl" type="text" placeholder="नोंदणी करणाऱ्याचे नाव" required />
      <input name="age" className="w-full p-3 border rounded-xl" type="number" placeholder="वय" required />

      <select name="gender" className="w-full p-3 border rounded-xl" required>
        <option>लिंग निवडा</option>
        <option>पुरुष</option>
        <option>महिला</option>
      </select>

      <input name="phone" className="w-full p-3 border rounded-xl" type="tel" placeholder="फोन नंबर" required />
      <textarea name="address" className="w-full p-3 border rounded-xl" rows="4" placeholder="पत्ता" required></textarea>

      <button
        type="submit"
        className="w-full bg-orange-600 hover:bg-orange-700 text-white font-semibold py-3 rounded-xl"
      >
        Submit Registration
      </button>
    </form>
  </div>
</div>

)h
isme marathi mai step by step
resistor karne wali ke information
1. name
2. age
3. gender male and female
4. phone number
5. address