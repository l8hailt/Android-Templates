#if (${PACKAGE_NAME} && ${PACKAGE_NAME} != "")package ${PACKAGE_NAME}#end

import android.content.Context
import android.view.LayoutInflater
import android.view.View
import android.view.ViewGroup
import androidx.recyclerview.widget.RecyclerView

#parse("File Header.java")
class ${NAME}(
    private val context:Context,
    private val items: List<${ITEM}>
) : RecyclerView.Adapter<${NAME}.${VIEW_HOLDER}>() {
   
    override fun onCreateViewHolder(parent: ViewGroup, viewType: Int): ${VIEW_HOLDER} {
        val v = LayoutInflater.from(context).inflate(R.layout.${LAYOUT}, parent, false)
        return ${VIEW_HOLDER}(v)
    }

    override fun onBindViewHolder(holder: ${VIEW_HOLDER}, position: Int) = holder.bind(items[position])

    override fun getItemCount(): Int = items.size
    
    inner class ${VIEW_HOLDER}(itemView: View) : RecyclerView.ViewHolder(itemView) {

        fun bind(item: ${ITEM}) {
            
        }
    }
 }
