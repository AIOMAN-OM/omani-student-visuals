# omani-student-visuals

مهارة (Skill) لتوليد حزمة من 24 صورة بوضعيات وزوايا وأساليب مختلفة لطلاب المدارس العُمانية من وصف أو صورة: صور رئيسية وزوايا تصوير، أوراق شخصية ووجه وعين، لوحات قصصية، صور سينمائية، نماذج كوب وتيشيرت، وورقتا ملصقات A4 — مع الالتزام بالزي المدرسي العُماني.

An agent skill that produces a full 24-image visual studio package for Omani school students (hero shots, camera-angle sets, character sheets, storyboards, mockups and A4 sticker sheets) following Omani school uniform rules.

## أمثلة من المخرجات | Examples

الحزمة الكاملة (24 صورة) من تجربة فعلية للمهارة في ChatGPT بطلب: «طالبة عُمانية، الصف الرابع» — وُلّدت على 4 دفعات، كل صورة مستقلة بوضعية وزاوية مختلفة، بدون أعلام أو شعارات أو نصوص.

The full 24-image default package from a real run of the skill ("Omani girl, grade 4"), generated in 4 batches — every image is a separate new generation with its own pose and camera angle.

| | | | |
|---|---|---|---|
| <img src="examples/package-24/01-hero.jpg" width="190"><br>01. Hero | <img src="examples/package-24/02-wide-courtyard.jpg" width="190"><br>02. Wide – courtyard walk | <img src="examples/package-24/03-medium-raise-hand.jpg" width="190"><br>03. Medium – raising hand | <img src="examples/package-24/04-closeup-reading.jpg" width="190"><br>04. Close-up – reading |
| <img src="examples/package-24/05-profile-whiteboard.jpg" width="190"><br>05. Profile – whiteboard | <img src="examples/package-24/06-drone-top-down.jpg" width="190"><br>06. Drone top-down | <img src="examples/package-24/07-turnaround-sheet.jpg" width="190"><br>07. Turnaround sheet | <img src="examples/package-24/08-face-angle-sheet.jpg" width="190"><br>08. Face-angle sheet |
| <img src="examples/package-24/09-eye-angle-sheet.jpg" width="190"><br>09. Eye-angle sheet | <img src="examples/package-24/10-portrait-expressions.jpg" width="190"><br>10. Portrait expressions | <img src="examples/package-24/11-cinematic-golden-hour.jpg" width="190"><br>11. Cinematic – golden hour | <img src="examples/package-24/12-editorial-studio.jpg" width="190"><br>12. Editorial – studio |
| <img src="examples/package-24/13-canon-50mm-library.jpg" width="190"><br>13. Canon 50mm – library | <img src="examples/package-24/14-canon-85mm-laughing.jpg" width="190"><br>14. Canon 85mm – laughing | <img src="examples/package-24/15-canon-70-200mm-science-fair.jpg" width="190"><br>15. Canon 70–200mm – science fair | <img src="examples/package-24/16-ground-level-ultrawide.jpg" width="190"><br>16. Ground-level ultra-wide |
| <img src="examples/package-24/17-mug-tshirt-mockup.jpg" width="190"><br>17. Mug & T-shirt mockup | <img src="examples/package-24/18-sticker-sheet-a4.jpg" width="190"><br>18. Assorted A4 stickers | <img src="examples/package-24/19-school-label-sheet-a4.jpg" width="190"><br>19. School-label A4 sheet | <img src="examples/package-24/20-storyboard-opening.jpg" width="190"><br>20. Storyboard – opening |
| <img src="examples/package-24/21-storyboard-closing.jpg" width="190"><br>21. Storyboard – closing | <img src="examples/package-24/22-over-the-shoulder-puzzle.jpg" width="190"><br>22. Over-the-shoulder – puzzle | <img src="examples/package-24/23-low-angle-stairs.jpg" width="190"><br>23. Low-angle – stairs | <img src="examples/package-24/24-watercolor-library.jpg" width="190"><br>24. Watercolor – library |

## Structure
- `SKILL.md` — main instructions
- `agents/openai.yaml` — display metadata
- `assets/icon.svg`

## Install
Copy the `omani-student-visuals` folder into your skills directory (e.g. `~/.claude/skills/`), or download the repo as ZIP and upload it as a skill.

By [AIOMAN](https://github.com/AIOMAN-OM)

## License

MIT — see [LICENSE](LICENSE).
