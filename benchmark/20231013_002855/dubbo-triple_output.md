# JMH version: 1.21
# VM version: JDK 1.8.0_382, OpenJDK 64-Bit Server VM, 25.382-b05
# VM invoker: /opt/hostedtoolcache/Java_Adopt_jdk/8.0.382-5/x64/jre/bin/java
# VM options: -Xmx1g -Xms1g -XX:MaxDirectMemorySize=1g -XX:+UseG1GC -Dserver.host=localhost -Dserver.port=8080 -Dbenchmark.output=dubbo-triple_output.md
# Warmup: 3 iterations, 10 s each
# Measurement: 3 iterations, 10 s each
# Timeout: 10 min per iteration
# Threads: 32 threads, will synchronize iterations
# Benchmark mode: Throughput, ops/time
# Benchmark: org.apache.dubbo.benchmark.ClientPb.createUser

# Run progress: 0.00% complete, ETA 00:12:00
# Fork: 1 of 1
# Warmup Iteration   1: 1.085 ops/ms
# Warmup Iteration   2: 2.271 ops/ms
# Warmup Iteration   3: 4.995 ops/ms
Iteration   1: 5.243 ops/ms
Iteration   2: 5.411 ops/ms
Iteration   3: 5.597 ops/ms


Result "org.apache.dubbo.benchmark.ClientPb.createUser":
  5.417 ±(99.9%) 3.234 ops/ms [Average]
  (min, avg, max) = (5.243, 5.417, 5.597), stdev = 0.177
  CI (99.9%): [2.183, 8.651] (assumes normal distribution)


# JMH version: 1.21
# VM version: JDK 1.8.0_382, OpenJDK 64-Bit Server VM, 25.382-b05
# VM invoker: /opt/hostedtoolcache/Java_Adopt_jdk/8.0.382-5/x64/jre/bin/java
# VM options: -Xmx1g -Xms1g -XX:MaxDirectMemorySize=1g -XX:+UseG1GC -Dserver.host=localhost -Dserver.port=8080 -Dbenchmark.output=dubbo-triple_output.md
# Warmup: 3 iterations, 10 s each
# Measurement: 3 iterations, 10 s each
# Timeout: 10 min per iteration
# Threads: 32 threads, will synchronize iterations
# Benchmark mode: Throughput, ops/time
# Benchmark: org.apache.dubbo.benchmark.ClientPb.existUser

# Run progress: 8.33% complete, ETA 00:12:18
# Fork: 1 of 1
# Warmup Iteration   1: 1.469 ops/ms
# Warmup Iteration   2: 4.572 ops/ms
# Warmup Iteration   3: 5.573 ops/ms
Iteration   1: 5.779 ops/ms
Iteration   2: 5.865 ops/ms
Iteration   3: 5.833 ops/ms


Result "org.apache.dubbo.benchmark.ClientPb.existUser":
  5.826 ±(99.9%) 0.791 ops/ms [Average]
  (min, avg, max) = (5.779, 5.826, 5.865), stdev = 0.043
  CI (99.9%): [5.035, 6.617] (assumes normal distribution)


# JMH version: 1.21
# VM version: JDK 1.8.0_382, OpenJDK 64-Bit Server VM, 25.382-b05
# VM invoker: /opt/hostedtoolcache/Java_Adopt_jdk/8.0.382-5/x64/jre/bin/java
# VM options: -Xmx1g -Xms1g -XX:MaxDirectMemorySize=1g -XX:+UseG1GC -Dserver.host=localhost -Dserver.port=8080 -Dbenchmark.output=dubbo-triple_output.md
# Warmup: 3 iterations, 10 s each
# Measurement: 3 iterations, 10 s each
# Timeout: 10 min per iteration
# Threads: 32 threads, will synchronize iterations
# Benchmark mode: Throughput, ops/time
# Benchmark: org.apache.dubbo.benchmark.ClientPb.getUser

# Run progress: 16.67% complete, ETA 00:11:05
# Fork: 1 of 1
# Warmup Iteration   1: 1.451 ops/ms
# Warmup Iteration   2: 4.199 ops/ms
# Warmup Iteration   3: 5.586 ops/ms
Iteration   1: 5.430 ops/ms
Iteration   2: 5.653 ops/ms
Iteration   3: 5.859 ops/ms


Result "org.apache.dubbo.benchmark.ClientPb.getUser":
  5.647 ±(99.9%) 3.912 ops/ms [Average]
  (min, avg, max) = (5.430, 5.647, 5.859), stdev = 0.214
  CI (99.9%): [1.736, 9.559] (assumes normal distribution)


# JMH version: 1.21
# VM version: JDK 1.8.0_382, OpenJDK 64-Bit Server VM, 25.382-b05
# VM invoker: /opt/hostedtoolcache/Java_Adopt_jdk/8.0.382-5/x64/jre/bin/java
# VM options: -Xmx1g -Xms1g -XX:MaxDirectMemorySize=1g -XX:+UseG1GC -Dserver.host=localhost -Dserver.port=8080 -Dbenchmark.output=dubbo-triple_output.md
# Warmup: 3 iterations, 10 s each
# Measurement: 3 iterations, 10 s each
# Timeout: 10 min per iteration
# Threads: 32 threads, will synchronize iterations
# Benchmark mode: Throughput, ops/time
# Benchmark: org.apache.dubbo.benchmark.ClientPb.listUser

# Run progress: 25.00% complete, ETA 00:09:56
# Fork: 1 of 1
# Warmup Iteration   1: 1.657 ops/ms
# Warmup Iteration   2: 3.744 ops/ms
# Warmup Iteration   3: 4.671 ops/ms
Iteration   1: 4.908 ops/ms
Iteration   2: 4.679 ops/ms
Iteration   3: 4.772 ops/ms


Result "org.apache.dubbo.benchmark.ClientPb.listUser":
  4.787 ±(99.9%) 2.099 ops/ms [Average]
  (min, avg, max) = (4.679, 4.787, 4.908), stdev = 0.115
  CI (99.9%): [2.688, 6.885] (assumes normal distribution)


# JMH version: 1.21
# VM version: JDK 1.8.0_382, OpenJDK 64-Bit Server VM, 25.382-b05
# VM invoker: /opt/hostedtoolcache/Java_Adopt_jdk/8.0.382-5/x64/jre/bin/java
# VM options: -Xmx1g -Xms1g -XX:MaxDirectMemorySize=1g -XX:+UseG1GC -Dserver.host=localhost -Dserver.port=8080 -Dbenchmark.output=dubbo-triple_output.md
# Warmup: 3 iterations, 10 s each
# Measurement: 3 iterations, 10 s each
# Timeout: 10 min per iteration
# Threads: 32 threads, will synchronize iterations
# Benchmark mode: Average time, time/op
# Benchmark: org.apache.dubbo.benchmark.ClientPb.createUser

# Run progress: 33.33% complete, ETA 00:08:51
# Fork: 1 of 1
# Warmup Iteration   1: 18.817 ±(99.9%) 0.143 ms/op
# Warmup Iteration   2: 6.926 ±(99.9%) 0.009 ms/op
# Warmup Iteration   3: 6.342 ±(99.9%) 0.007 ms/op
Iteration   1: 5.877 ±(99.9%) 0.012 ms/op
Iteration   2: 5.809 ±(99.9%) 0.011 ms/op
Iteration   3: 5.781 ±(99.9%) 0.013 ms/op


Result "org.apache.dubbo.benchmark.ClientPb.createUser":
  5.823 ±(99.9%) 0.893 ms/op [Average]
  (min, avg, max) = (5.781, 5.823, 5.877), stdev = 0.049
  CI (99.9%): [4.929, 6.716] (assumes normal distribution)


# JMH version: 1.21
# VM version: JDK 1.8.0_382, OpenJDK 64-Bit Server VM, 25.382-b05
# VM invoker: /opt/hostedtoolcache/Java_Adopt_jdk/8.0.382-5/x64/jre/bin/java
# VM options: -Xmx1g -Xms1g -XX:MaxDirectMemorySize=1g -XX:+UseG1GC -Dserver.host=localhost -Dserver.port=8080 -Dbenchmark.output=dubbo-triple_output.md
# Warmup: 3 iterations, 10 s each
# Measurement: 3 iterations, 10 s each
# Timeout: 10 min per iteration
# Threads: 32 threads, will synchronize iterations
# Benchmark mode: Average time, time/op
# Benchmark: org.apache.dubbo.benchmark.ClientPb.existUser

# Run progress: 41.67% complete, ETA 00:07:45
# Fork: 1 of 1
# Warmup Iteration   1: 17.931 ±(99.9%) 0.074 ms/op
# Warmup Iteration   2: 6.692 ±(99.9%) 0.009 ms/op
# Warmup Iteration   3: 5.582 ±(99.9%) 0.010 ms/op
Iteration   1: 5.779 ±(99.9%) 0.007 ms/op
Iteration   2: 5.618 ±(99.9%) 0.008 ms/op
Iteration   3: 5.514 ±(99.9%) 0.015 ms/op


Result "org.apache.dubbo.benchmark.ClientPb.existUser":
  5.637 ±(99.9%) 2.436 ms/op [Average]
  (min, avg, max) = (5.514, 5.637, 5.779), stdev = 0.134
  CI (99.9%): [3.201, 8.074] (assumes normal distribution)


# JMH version: 1.21
# VM version: JDK 1.8.0_382, OpenJDK 64-Bit Server VM, 25.382-b05
# VM invoker: /opt/hostedtoolcache/Java_Adopt_jdk/8.0.382-5/x64/jre/bin/java
# VM options: -Xmx1g -Xms1g -XX:MaxDirectMemorySize=1g -XX:+UseG1GC -Dserver.host=localhost -Dserver.port=8080 -Dbenchmark.output=dubbo-triple_output.md
# Warmup: 3 iterations, 10 s each
# Measurement: 3 iterations, 10 s each
# Timeout: 10 min per iteration
# Threads: 32 threads, will synchronize iterations
# Benchmark mode: Average time, time/op
# Benchmark: org.apache.dubbo.benchmark.ClientPb.getUser

# Run progress: 50.00% complete, ETA 00:06:39
# Fork: 1 of 1
# Warmup Iteration   1: 20.172 ±(99.9%) 0.088 ms/op
# Warmup Iteration   2: 7.440 ±(99.9%) 0.010 ms/op
# Warmup Iteration   3: 5.849 ±(99.9%) 0.012 ms/op
Iteration   1: 5.667 ±(99.9%) 0.008 ms/op
Iteration   2: 5.468 ±(99.9%) 0.014 ms/op
Iteration   3: 5.758 ±(99.9%) 0.009 ms/op


Result "org.apache.dubbo.benchmark.ClientPb.getUser":
  5.631 ±(99.9%) 2.705 ms/op [Average]
  (min, avg, max) = (5.468, 5.631, 5.758), stdev = 0.148
  CI (99.9%): [2.927, 8.336] (assumes normal distribution)


# JMH version: 1.21
# VM version: JDK 1.8.0_382, OpenJDK 64-Bit Server VM, 25.382-b05
# VM invoker: /opt/hostedtoolcache/Java_Adopt_jdk/8.0.382-5/x64/jre/bin/java
# VM options: -Xmx1g -Xms1g -XX:MaxDirectMemorySize=1g -XX:+UseG1GC -Dserver.host=localhost -Dserver.port=8080 -Dbenchmark.output=dubbo-triple_output.md
# Warmup: 3 iterations, 10 s each
# Measurement: 3 iterations, 10 s each
# Timeout: 10 min per iteration
# Threads: 32 threads, will synchronize iterations
# Benchmark mode: Average time, time/op
# Benchmark: org.apache.dubbo.benchmark.ClientPb.listUser

# Run progress: 58.33% complete, ETA 00:05:32
# Fork: 1 of 1
# Warmup Iteration   1: 20.400 ±(99.9%) 0.090 ms/op
# Warmup Iteration   2: 7.926 ±(99.9%) 0.011 ms/op
# Warmup Iteration   3: 6.839 ±(99.9%) 0.014 ms/op
Iteration   1: 6.652 ±(99.9%) 0.011 ms/op
Iteration   2: 6.777 ±(99.9%) 0.011 ms/op
Iteration   3: 6.866 ±(99.9%) 0.014 ms/op


Result "org.apache.dubbo.benchmark.ClientPb.listUser":
  6.765 ±(99.9%) 1.964 ms/op [Average]
  (min, avg, max) = (6.652, 6.765, 6.866), stdev = 0.108
  CI (99.9%): [4.801, 8.729] (assumes normal distribution)


# JMH version: 1.21
# VM version: JDK 1.8.0_382, OpenJDK 64-Bit Server VM, 25.382-b05
# VM invoker: /opt/hostedtoolcache/Java_Adopt_jdk/8.0.382-5/x64/jre/bin/java
# VM options: -Xmx1g -Xms1g -XX:MaxDirectMemorySize=1g -XX:+UseG1GC -Dserver.host=localhost -Dserver.port=8080 -Dbenchmark.output=dubbo-triple_output.md
# Warmup: 3 iterations, 10 s each
# Measurement: 3 iterations, 10 s each
# Timeout: 10 min per iteration
# Threads: 32 threads, will synchronize iterations
# Benchmark mode: Sampling time
# Benchmark: org.apache.dubbo.benchmark.ClientPb.createUser

# Run progress: 66.67% complete, ETA 00:04:25
# Fork: 1 of 1
# Warmup Iteration   1: 19.632 ±(99.9%) 0.340 ms/op
# Warmup Iteration   2: 7.377 ±(99.9%) 0.048 ms/op
# Warmup Iteration   3: 5.950 ±(99.9%) 0.030 ms/op
Iteration   1: 6.047 ±(99.9%) 0.029 ms/op
                 createUser·p0.00:   1.860 ms/op
                 createUser·p0.50:   5.628 ms/op
                 createUser·p0.90:   8.004 ms/op
                 createUser·p0.95:   9.241 ms/op
                 createUser·p0.99:   13.369 ms/op
                 createUser·p0.999:  28.934 ms/op
                 createUser·p0.9999: 33.910 ms/op
                 createUser·p1.00:   34.472 ms/op

Iteration   2: 5.759 ±(99.9%) 0.029 ms/op
                 createUser·p0.00:   2.310 ms/op
                 createUser·p0.50:   5.226 ms/op
                 createUser·p0.90:   7.561 ms/op
                 createUser·p0.95:   8.765 ms/op
                 createUser·p0.99:   12.630 ms/op
                 createUser·p0.999:  21.201 ms/op
                 createUser·p0.9999: 55.239 ms/op
                 createUser·p1.00:   55.706 ms/op

Iteration   3: 5.682 ±(99.9%) 0.032 ms/op
                 createUser·p0.00:   1.989 ms/op
                 createUser·p0.50:   5.054 ms/op
                 createUser·p0.90:   7.367 ms/op
                 createUser·p0.95:   8.782 ms/op
                 createUser·p0.99:   12.468 ms/op
                 createUser·p0.999:  34.940 ms/op
                 createUser·p0.9999: 65.403 ms/op
                 createUser·p1.00:   71.565 ms/op



Result "org.apache.dubbo.benchmark.ClientPb.createUser":
  N = 164779
  mean =      5.825 ±(99.9%) 0.017 ms/op

  Histogram, ms/op:
    [ 0.000,  5.000) = 63819 
    [ 5.000, 10.000) = 96314 
    [10.000, 15.000) = 3733 
    [15.000, 20.000) = 575 
    [20.000, 25.000) = 104 
    [25.000, 30.000) = 82 
    [30.000, 35.000) = 65 
    [35.000, 40.000) = 23 
    [40.000, 45.000) = 0 
    [45.000, 50.000) = 5 
    [50.000, 55.000) = 24 
    [55.000, 60.000) = 7 
    [60.000, 65.000) = 22 
    [65.000, 70.000) = 3 
    [70.000, 75.000) = 3 

  Percentiles, ms/op:
      p(0.0000) =      1.860 ms/op
     p(50.0000) =      5.292 ms/op
     p(90.0000) =      7.668 ms/op
     p(95.0000) =      8.929 ms/op
     p(99.0000) =     12.845 ms/op
     p(99.9000) =     29.061 ms/op
     p(99.9900) =     64.006 ms/op
     p(99.9990) =     70.631 ms/op
     p(99.9999) =     71.565 ms/op
    p(100.0000) =     71.565 ms/op


# JMH version: 1.21
# VM version: JDK 1.8.0_382, OpenJDK 64-Bit Server VM, 25.382-b05
# VM invoker: /opt/hostedtoolcache/Java_Adopt_jdk/8.0.382-5/x64/jre/bin/java
# VM options: -Xmx1g -Xms1g -XX:MaxDirectMemorySize=1g -XX:+UseG1GC -Dserver.host=localhost -Dserver.port=8080 -Dbenchmark.output=dubbo-triple_output.md
# Warmup: 3 iterations, 10 s each
# Measurement: 3 iterations, 10 s each
# Timeout: 10 min per iteration
# Threads: 32 threads, will synchronize iterations
# Benchmark mode: Sampling time
# Benchmark: org.apache.dubbo.benchmark.ClientPb.existUser

# Run progress: 75.00% complete, ETA 00:03:19
# Fork: 1 of 1
# Warmup Iteration   1: 17.196 ±(99.9%) 0.290 ms/op
# Warmup Iteration   2: 6.803 ±(99.9%) 0.044 ms/op
# Warmup Iteration   3: 5.613 ±(99.9%) 0.023 ms/op
Iteration   1: 5.665 ±(99.9%) 0.024 ms/op
                 existUser·p0.00:   2.441 ms/op
                 existUser·p0.50:   5.218 ms/op
                 existUser·p0.90:   7.365 ms/op
                 existUser·p0.95:   8.536 ms/op
                 existUser·p0.99:   12.059 ms/op
                 existUser·p0.999:  25.297 ms/op
                 existUser·p0.9999: 34.167 ms/op
                 existUser·p1.00:   34.996 ms/op

Iteration   2: 5.622 ±(99.9%) 0.026 ms/op
                 existUser·p0.00:   1.839 ms/op
                 existUser·p0.50:   4.989 ms/op
                 existUser·p0.90:   7.799 ms/op
                 existUser·p0.95:   9.404 ms/op
                 existUser·p0.99:   12.747 ms/op
                 existUser·p0.999:  26.804 ms/op
                 existUser·p0.9999: 29.950 ms/op
                 existUser·p1.00:   30.343 ms/op

Iteration   3: 5.543 ±(99.9%) 0.021 ms/op
                 existUser·p0.00:   2.019 ms/op
                 existUser·p0.50:   5.153 ms/op
                 existUser·p0.90:   7.029 ms/op
                 existUser·p0.95:   8.266 ms/op
                 existUser·p0.99:   11.158 ms/op
                 existUser·p0.999:  19.769 ms/op
                 existUser·p0.9999: 30.908 ms/op
                 existUser·p1.00:   31.654 ms/op



Result "org.apache.dubbo.benchmark.ClientPb.existUser":
  N = 171145
  mean =      5.609 ±(99.9%) 0.014 ms/op

  Histogram, ms/op:
    [ 0.000,  2.500) = 24 
    [ 2.500,  5.000) = 75574 
    [ 5.000,  7.500) = 79715 
    [ 7.500, 10.000) = 11457 
    [10.000, 12.500) = 3038 
    [12.500, 15.000) = 758 
    [15.000, 17.500) = 266 
    [17.500, 20.000) = 76 
    [20.000, 22.500) = 61 
    [22.500, 25.000) = 14 
    [25.000, 27.500) = 58 
    [27.500, 30.000) = 61 
    [30.000, 32.500) = 27 
    [32.500, 35.000) = 16 
    [35.000, 37.500) = 0 

  Percentiles, ms/op:
      p(0.0000) =      1.839 ms/op
     p(50.0000) =      5.120 ms/op
     p(90.0000) =      7.356 ms/op
     p(95.0000) =      8.716 ms/op
     p(99.0000) =     11.960 ms/op
     p(99.9000) =     23.125 ms/op
     p(99.9900) =     32.458 ms/op
     p(99.9990) =     34.810 ms/op
     p(99.9999) =     34.996 ms/op
    p(100.0000) =     34.996 ms/op


# JMH version: 1.21
# VM version: JDK 1.8.0_382, OpenJDK 64-Bit Server VM, 25.382-b05
# VM invoker: /opt/hostedtoolcache/Java_Adopt_jdk/8.0.382-5/x64/jre/bin/java
# VM options: -Xmx1g -Xms1g -XX:MaxDirectMemorySize=1g -XX:+UseG1GC -Dserver.host=localhost -Dserver.port=8080 -Dbenchmark.output=dubbo-triple_output.md
# Warmup: 3 iterations, 10 s each
# Measurement: 3 iterations, 10 s each
# Timeout: 10 min per iteration
# Threads: 32 threads, will synchronize iterations
# Benchmark mode: Sampling time
# Benchmark: org.apache.dubbo.benchmark.ClientPb.getUser

# Run progress: 83.33% complete, ETA 00:02:13
# Fork: 1 of 1
# Warmup Iteration   1: 18.349 ±(99.9%) 0.291 ms/op
# Warmup Iteration   2: 6.926 ±(99.9%) 0.047 ms/op
# Warmup Iteration   3: 5.917 ±(99.9%) 0.026 ms/op
Iteration   1: 6.016 ±(99.9%) 0.027 ms/op
                 getUser·p0.00:   2.269 ms/op
                 getUser·p0.50:   5.652 ms/op
                 getUser·p0.90:   7.602 ms/op
                 getUser·p0.95:   8.880 ms/op
                 getUser·p0.99:   13.508 ms/op
                 getUser·p0.999:  26.935 ms/op
                 getUser·p0.9999: 31.523 ms/op
                 getUser·p1.00:   31.654 ms/op

Iteration   2: 6.079 ±(99.9%) 0.028 ms/op
                 getUser·p0.00:   2.478 ms/op
                 getUser·p0.50:   5.521 ms/op
                 getUser·p0.90:   8.258 ms/op
                 getUser·p0.95:   9.847 ms/op
                 getUser·p0.99:   13.844 ms/op
                 getUser·p0.999:  24.228 ms/op
                 getUser·p0.9999: 29.200 ms/op
                 getUser·p1.00:   30.900 ms/op

Iteration   3: 5.813 ±(99.9%) 0.026 ms/op
                 getUser·p0.00:   1.323 ms/op
                 getUser·p0.50:   5.284 ms/op
                 getUser·p0.90:   7.487 ms/op
                 getUser·p0.95:   9.044 ms/op
                 getUser·p0.99:   12.861 ms/op
                 getUser·p0.999:  26.739 ms/op
                 getUser·p0.9999: 34.210 ms/op
                 getUser·p1.00:   35.258 ms/op



Result "org.apache.dubbo.benchmark.ClientPb.getUser":
  N = 160760
  mean =      5.967 ±(99.9%) 0.016 ms/op

  Histogram, ms/op:
    [ 0.000,  2.500) = 17 
    [ 2.500,  5.000) = 44874 
    [ 5.000,  7.500) = 97947 
    [ 7.500, 10.000) = 11922 
    [10.000, 12.500) = 3693 
    [12.500, 15.000) = 1420 
    [15.000, 17.500) = 391 
    [17.500, 20.000) = 193 
    [20.000, 22.500) = 61 
    [22.500, 25.000) = 66 
    [25.000, 27.500) = 70 
    [27.500, 30.000) = 60 
    [30.000, 32.500) = 33 
    [32.500, 35.000) = 11 
    [35.000, 37.500) = 2 

  Percentiles, ms/op:
      p(0.0000) =      1.323 ms/op
     p(50.0000) =      5.489 ms/op
     p(90.0000) =      7.717 ms/op
     p(95.0000) =      9.388 ms/op
     p(99.0000) =     13.484 ms/op
     p(99.9000) =     26.247 ms/op
     p(99.9900) =     32.211 ms/op
     p(99.9990) =     35.179 ms/op
     p(99.9999) =     35.258 ms/op
    p(100.0000) =     35.258 ms/op


# JMH version: 1.21
# VM version: JDK 1.8.0_382, OpenJDK 64-Bit Server VM, 25.382-b05
# VM invoker: /opt/hostedtoolcache/Java_Adopt_jdk/8.0.382-5/x64/jre/bin/java
# VM options: -Xmx1g -Xms1g -XX:MaxDirectMemorySize=1g -XX:+UseG1GC -Dserver.host=localhost -Dserver.port=8080 -Dbenchmark.output=dubbo-triple_output.md
# Warmup: 3 iterations, 10 s each
# Measurement: 3 iterations, 10 s each
# Timeout: 10 min per iteration
# Threads: 32 threads, will synchronize iterations
# Benchmark mode: Sampling time
# Benchmark: org.apache.dubbo.benchmark.ClientPb.listUser

# Run progress: 91.67% complete, ETA 00:01:06
# Fork: 1 of 1
# Warmup Iteration   1: 21.914 ±(99.9%) 0.416 ms/op
# Warmup Iteration   2: 8.667 ±(99.9%) 0.073 ms/op
# Warmup Iteration   3: 6.934 ±(99.9%) 0.036 ms/op
Iteration   1: 7.109 ±(99.9%) 0.039 ms/op
                 listUser·p0.00:   2.634 ms/op
                 listUser·p0.50:   6.382 ms/op
                 listUser·p0.90:   9.912 ms/op
                 listUser·p0.95:   11.354 ms/op
                 listUser·p0.99:   16.611 ms/op
                 listUser·p0.999:  30.932 ms/op
                 listUser·p0.9999: 34.374 ms/op
                 listUser·p1.00:   39.322 ms/op

Iteration   2: 6.963 ±(99.9%) 0.035 ms/op
                 listUser·p0.00:   2.519 ms/op
                 listUser·p0.50:   6.291 ms/op
                 listUser·p0.90:   9.437 ms/op
                 listUser·p0.95:   11.141 ms/op
                 listUser·p0.99:   16.089 ms/op
                 listUser·p0.999:  28.414 ms/op
                 listUser·p0.9999: 30.894 ms/op
                 listUser·p1.00:   31.916 ms/op

Iteration   3: 6.587 ±(99.9%) 0.029 ms/op
                 listUser·p0.00:   1.888 ms/op
                 listUser·p0.50:   6.038 ms/op
                 listUser·p0.90:   8.421 ms/op
                 listUser·p0.95:   9.929 ms/op
                 listUser·p0.99:   13.533 ms/op
                 listUser·p0.999:  29.120 ms/op
                 listUser·p0.9999: 35.885 ms/op
                 listUser·p1.00:   36.569 ms/op



Result "org.apache.dubbo.benchmark.ClientPb.listUser":
  N = 139533
  mean =      6.879 ±(99.9%) 0.020 ms/op

  Histogram, ms/op:
    [ 0.000,  2.500) = 3 
    [ 2.500,  5.000) = 5024 
    [ 5.000,  7.500) = 105363 
    [ 7.500, 10.000) = 18783 
    [10.000, 12.500) = 6764 
    [12.500, 15.000) = 2036 
    [15.000, 17.500) = 677 
    [17.500, 20.000) = 268 
    [20.000, 22.500) = 170 
    [22.500, 25.000) = 97 
    [25.000, 27.500) = 111 
    [27.500, 30.000) = 132 
    [30.000, 32.500) = 51 
    [32.500, 35.000) = 41 
    [35.000, 37.500) = 12 

  Percentiles, ms/op:
      p(0.0000) =      1.888 ms/op
     p(50.0000) =      6.234 ms/op
     p(90.0000) =      9.257 ms/op
     p(95.0000) =     10.830 ms/op
     p(99.0000) =     15.352 ms/op
     p(99.9000) =     29.131 ms/op
     p(99.9900) =     34.749 ms/op
     p(99.9990) =     38.233 ms/op
     p(99.9999) =     39.322 ms/op
    p(100.0000) =     39.322 ms/op


# Run complete. Total time: 00:13:19

REMEMBER: The numbers below are just data. To gain reusable insights, you need to follow up on
why the numbers are the way they are. Use profilers (see -prof, -lprof), design factorial
experiments, perform baseline and negative tests that provide experimental control, make sure
the benchmarking environment is safe on JVM/OS/HW level, ask for reviews from the domain experts.
Do not assume the numbers tell you what you want them to tell.

Benchmark                                 Mode     Cnt   Score   Error   Units
ClientPb.createUser                      thrpt       3   5.417 ± 3.234  ops/ms
ClientPb.existUser                       thrpt       3   5.826 ± 0.791  ops/ms
ClientPb.getUser                         thrpt       3   5.647 ± 3.912  ops/ms
ClientPb.listUser                        thrpt       3   4.787 ± 2.099  ops/ms
ClientPb.createUser                       avgt       3   5.823 ± 0.893   ms/op
ClientPb.existUser                        avgt       3   5.637 ± 2.436   ms/op
ClientPb.getUser                          avgt       3   5.631 ± 2.705   ms/op
ClientPb.listUser                         avgt       3   6.765 ± 1.964   ms/op
ClientPb.createUser                     sample  164779   5.825 ± 0.017   ms/op
ClientPb.createUser:createUser·p0.00    sample           1.860           ms/op
ClientPb.createUser:createUser·p0.50    sample           5.292           ms/op
ClientPb.createUser:createUser·p0.90    sample           7.668           ms/op
ClientPb.createUser:createUser·p0.95    sample           8.929           ms/op
ClientPb.createUser:createUser·p0.99    sample          12.845           ms/op
ClientPb.createUser:createUser·p0.999   sample          29.061           ms/op
ClientPb.createUser:createUser·p0.9999  sample          64.006           ms/op
ClientPb.createUser:createUser·p1.00    sample          71.565           ms/op
ClientPb.existUser                      sample  171145   5.609 ± 0.014   ms/op
ClientPb.existUser:existUser·p0.00      sample           1.839           ms/op
ClientPb.existUser:existUser·p0.50      sample           5.120           ms/op
ClientPb.existUser:existUser·p0.90      sample           7.356           ms/op
ClientPb.existUser:existUser·p0.95      sample           8.716           ms/op
ClientPb.existUser:existUser·p0.99      sample          11.960           ms/op
ClientPb.existUser:existUser·p0.999     sample          23.125           ms/op
ClientPb.existUser:existUser·p0.9999    sample          32.458           ms/op
ClientPb.existUser:existUser·p1.00      sample          34.996           ms/op
ClientPb.getUser                        sample  160760   5.967 ± 0.016   ms/op
ClientPb.getUser:getUser·p0.00          sample           1.323           ms/op
ClientPb.getUser:getUser·p0.50          sample           5.489           ms/op
ClientPb.getUser:getUser·p0.90          sample           7.717           ms/op
ClientPb.getUser:getUser·p0.95          sample           9.388           ms/op
ClientPb.getUser:getUser·p0.99          sample          13.484           ms/op
ClientPb.getUser:getUser·p0.999         sample          26.247           ms/op
ClientPb.getUser:getUser·p0.9999        sample          32.211           ms/op
ClientPb.getUser:getUser·p1.00          sample          35.258           ms/op
ClientPb.listUser                       sample  139533   6.879 ± 0.020   ms/op
ClientPb.listUser:listUser·p0.00        sample           1.888           ms/op
ClientPb.listUser:listUser·p0.50        sample           6.234           ms/op
ClientPb.listUser:listUser·p0.90        sample           9.257           ms/op
ClientPb.listUser:listUser·p0.95        sample          10.830           ms/op
ClientPb.listUser:listUser·p0.99        sample          15.352           ms/op
ClientPb.listUser:listUser·p0.999       sample          29.131           ms/op
ClientPb.listUser:listUser·p0.9999      sample          34.749           ms/op
ClientPb.listUser:listUser·p1.00        sample          39.322           ms/op
