# gatsby-faq

# Example

    array.map((el) => (
      <QuestionWrapper>
        <Question>{el.question}</Question>
        <Answer>{el.answer}</Answer>
      </QuestionWrapper>
    )
    
# Style details
    --details - wrapper
        --summary - question
            --span - question text
        --p  - answer
            --span - answer text
