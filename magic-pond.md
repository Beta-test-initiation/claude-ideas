Prompt:

• create an infinite-loop animated background i can embed in the hero section of my [framer/webflow/vercel] site. palette: [hex codes or describe vibe]. keep it subtle — it should sit behind text, not compete with it.
• make a continuously animating background inspired by [attach reference image]. match the color palette and overall mood, but don’t copy it directly.

steering the look
• more like the reference — the [ripples/waves/blobs] should be [more concentric / less uniform / patchier]. right now they look too [perfect/blurred/symmetric].

realism & detail
• how can we make this look more like real water/clouds/fabric? list a few options and pick the most subtle combination.

making it loop seamlessly
• the animation has a visible jump at the loop point. make it seamless — match start and end values, or use palindromic keyframes.
• what is spline easing and where would it help here? (genuinely useful for understanding svg <animate> polish)

performance
• profile what’s expensive on cursor-move. propose 2–3 options ranging from minor to aggressive surgery, with the visual trade-off each makes.
• rasterize anything that doesn’t truly need to be live svg — animate cheap bitmap transforms instead of re-running filters every frame.
• target 60fps on a mid-tier laptop. keep the look, change the implementation.

interactivity (optional)
• make one element subtly follow my cursor with a lazy lag, not a snappy track. keep the rest of the motion intact.

export & integration
• how do i add this to framer? walk me through the exact steps for the [html embed / iframe] approach.

process meta-prompts (these save the most time)
• what’s the cheapest visual change that would address this without doing a full rebuild?
• show me 2–3 variants of [the color/the motion/the density] side by side via the tweaks panel so i can a/b them.



<img width="356" height="153" alt="Screenshot 2026-05-25 at 4 32 08 PM" src="https://github.com/user-attachments/assets/1dfca14a-a346-4c67-bc97-07a51e9aa70f" />


https://www.instagram.com/p/DYvZw4NPBca/
