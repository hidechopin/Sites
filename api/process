export default function handler(req, res) {
  const text = req.query.text || "";
  const reversed = text.split("").reverse().join("");
  res.status(200).json({ result: reversed });
}
