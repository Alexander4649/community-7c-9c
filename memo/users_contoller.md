  #   @currentUserEntry=Entry.where(user_id: current_user.id)
  #   @userEntry=Entry.where(user_id: @user.id)
    
  #   unless @user.id == current_user.id
  #     @currentUserEntry.each do |cu|
  #       @userEntry.each do |u|
  #         if cu.room_id == u.room_id then #ブロックの評価値が戻る then
  #           @isRoom = true
  #           @roomId = cu.room_id
  #         end
  #       end
  #     end
  #     if @isRoom
  #     else
  #       @room = Room.new
  #       @entry = Entry.new
  #     end
  #   end