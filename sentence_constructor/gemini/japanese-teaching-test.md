<prompt_improvement_guide>
  <section title="Ways to Improve and Enhance Your Prompt">
    <improvement_area>
      <title>Clarity and Specificity of Instructions</title>
      <point>
        <sub_point>For the AI Agent:</sub_point>
        Are all instructions for the AI agent crystal clear and unambiguous? Could any instruction be misinterpreted? Are rules for vocabulary tables, sentence structures, and clues perfectly defined? Consider adding more detail or examples if needed.
      </point>
      <point>
        <sub_point>For the Student (Implicit):</sub_point>
        Consider if the flow is intuitive for a student. Is it clear what to do at each stage? Does it feel like a natural learning progression?
      </point>
    </improvement_area>

    <improvement_area>
      <title>Vocabulary Table Enhancement</title>
      <point>
        <sub_point>Relevance:</sub_point>
        Is the vocabulary provided always the most relevant and helpful for the target sentence? Are there any words consistently missing that would be useful?
      </point>
      <point>
        <sub_point>Beginner-Friendliness:</sub_point>
        Are the words themselves appropriate for JLPT N5 level? Are there any words that might be too complex or uncommon for beginners?
      </point>
      <point>
        <sub_point>Examples (Optional):</sub_point>
        Consider adding very simple example sentences within the vocabulary table to illustrate word usage (optional, depending on desired guidance level).
      </point>
      <point>
        <sub_point>Categorization (Optional):</sub_point>
        Could categorizing vocabulary (nouns, verbs, adjectives) make it easier for students to process?
      </point>
    </improvement_area>

    <improvement_area>
      <title>Sentence Structure Examples - Refinement</title>
      <point>
        <sub_point>Abstraction Level:</sub_point>
        Are sentence structures too abstract or just right for beginners? Could they be more concrete (e.g., adding a simplified English example) without giving away the answer?
      </point>
      <point>
        <sub_point>Coverage:</sub_point>
        Do sentence structure examples adequately cover grammatical patterns for expected sentences? Are there missing common patterns?
      </point>
      <point>
        <sub_point>Number of Examples:</sub_point>
        Are two example structures sufficient, or would more or fewer be better for clarity without overwhelming the student?
      </point>
    </improvement_area>

    <improvement_area>
      <title>Clues and Hints - Fine-tuning</title>
      <point>
        <sub_point>Effectiveness:</sub_point>
        Are current clues genuinely helpful without giving away the answer? Are they too vague or too obvious?
      </point>
      <point>
        <sub_point>Variety:</sub_point>
        Could you introduce different types of clues (Grammar, Particle, Vocabulary, Structure Clues)? Provide examples like: "Remember verb conjugation", "Think about location particle", "Another word for office?", "Look at structure example #2".
      </point>
      <point>
        <sub_point>Progressive Hints:</sub_point>
        Design a system of progressively specific hints for students who struggle (vague -> more direct -> targeted).
      </point>
    </improvement_area>

    <improvement_area>
      <title>State Transitions and Agent Flow</title>
      <point>
        <sub_point>Completeness:</sub_point>
        Does the state diagram (Setup -> Attempt -> Clues etc.) cover all necessary interactions? Are there missing states or transitions?
      </point>
      <point>
        <sub_point>Smoothness:</sub_point>
        Does the flow feel natural and logical for a student? Is it clear how to move between states?
      </point>
      <point>
        <sub_point>"Stuck" State Handling:</sub_point>
        What happens if a student is stuck? Is there a mechanism to offer more direct help or move to a different exercise?
      </point>
    </improvement_area>

    <improvement_area>
      <title>Error Handling and Feedback</title>
      <point>
        <sub_point>Incorrect Attempts:</sub_point>
        Is feedback for incorrect Japanese sentences specific, helpful, and encouraging? Is it potentially demotivating?
      </point>
      <point>
        <sub_point>Unclear Input:</sub_point>
        How does the prompt handle non-sentence student inputs or unrelated questions? (Address "Target English Sentence" section).
      </point>
      <point>
        <sub_point>Patience and Persistence:</sub_point>
        Does the prompt maintain a patient and helpful tone even with repeated student mistakes?
      </point>
    </improvement_area>
  </section>

  <section title="Multiple Ways to Test Your Prompt">
    <testing_method>
      <title>"Think-Aloud" Self-Testing</title>
      <point>
        <sub_point>Be the Student:</sub_point>
        Go through the prompt as a beginner Japanese student. Translate sentences using only provided materials.
      </point>
      <point>
        <sub_point>Verbalize Your Process:</sub_point>
        Describe your thinking aloud (record if possible): what's confusing, helpful, where you get stuck, and what you try.
      </point>
      <point>
        <sub_point>Identify Pain Points:</sub_point>
        Note moments of confusion, frustration, or insufficient guidance for improvement areas.
      </point>
    </testing_method>

    <testing_method>
      <title>Internal AI Testing (Simulated Student)</title>
      <point>
        <sub_point>Vary Student Inputs:</sub_point>
        Test with: Correct Answer, Partially Correct Answer, Incorrect Answer (common mistakes), Student Questions, Nonsense Input.
      </point>
      <point>
        <sub_point>Evaluate AI Output:</sub_point>
        For each input, analyze if the AI output is: Consistent, Helpful, Appropriate Level, Non-Revealing, Grammatically Sound.
      </point>
    </testing_method>

    <testing_method>
      <title>"Simulated User" Testing (with another person)</title>
      <point>
        <sub_point>Explain the Role:</sub_point>
        Ask someone to act as a beginner student, explain the prompt's goal and scenario.
      </point>
      <point>
        <sub_point>Provide Scenarios:</sub_point>
        Give them English sentences to translate.
      </point>
      <point>
        <sub_point>Observe and Take Notes:</sub_point>
        Watch their interaction, note reactions, questions, struggles, and successes.
      </point>
      <point>
        <sub_point>Gather Verbal Feedback:</sub_point>
        Ask: "What was helpful?", "What was confusing?", "Where did you feel stuck?", "Did you feel like you were learning?", "What could be improved?".
      </point>
    </testing_method>

    <testing_method>
      <title>Real Beginner User Testing (Ideal)</title>
      <point>
        <sub_point>Find Beginner Learners:</sub_point>
        Test with actual beginner Japanese learners.
      </point>
      <point>
        <sub_point>Ethical Considerations:</sub_point>
        Ensure they know it's a test, their feedback is valuable, and don't pressure them.
      </point>
      <point>
        <sub_point>Gather Feedback:</sub_point>
        Use questionnaires, interviews, or observation to get honest opinions.
      </point>
    </testing_method>

    <testing_method>
      <title>Iterative Refinement</title>
      <point>
        <sub_point>Cycle of Test &amp; Improve:</sub_point>
        Testing is iterative. Use feedback to identify weaknesses.
      </point>
      <point>
        <sub_point>Revise the Prompt:</sub_point>
        Make specific changes based on feedback (instructions, vocab, clues, structures).
      </point>
      <point>
        <sub_point>Re-test:</sub_point>
        Re-test improved prompt. Repeat cycle.
      </point>
    </testing_method>
  </section>
</prompt_improvement_guide>