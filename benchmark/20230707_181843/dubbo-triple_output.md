# JMH version: 1.21
# VM version: JDK 1.8.0_372, OpenJDK 64-Bit Server VM, 25.372-b07
# VM invoker: /opt/hostedtoolcache/Java_Adopt_jdk/8.0.372-7/x64/jre/bin/java
# VM options: -Xmx1g -Xms1g -XX:MaxDirectMemorySize=1g -XX:+UseG1GC -Dserver.host=localhost -Dserver.port=8080 -Dbenchmark.output=dubbo-triple_output.md
# Warmup: 3 iterations, 10 s each
# Measurement: 3 iterations, 10 s each
# Timeout: 10 min per iteration
# Threads: 32 threads, will synchronize iterations
# Benchmark mode: Throughput, ops/time
# Benchmark: org.apache.dubbo.benchmark.ClientPb.createUser

# Run progress: 0.00% complete, ETA 00:12:00
# Fork: 1 of 1
# Warmup Iteration   1: 1.599 ops/ms
# Warmup Iteration   2: 3.395 ops/ms
# Warmup Iteration   3: 7.217 ops/ms
Iteration   1: 7.485 ops/ms
Iteration   2: 7.785 ops/ms
Iteration   3: 7.920 ops/ms


Result "org.apache.dubbo.benchmark.ClientPb.createUser":
  7.730 ±(99.9%) 4.062 ops/ms [Average]
  (min, avg, max) = (7.485, 7.730, 7.920), stdev = 0.223
  CI (99.9%): [3.667, 11.792] (assumes normal distribution)


# JMH version: 1.21
# VM version: JDK 1.8.0_372, OpenJDK 64-Bit Server VM, 25.372-b07
# VM invoker: /opt/hostedtoolcache/Java_Adopt_jdk/8.0.372-7/x64/jre/bin/java
# VM options: -Xmx1g -Xms1g -XX:MaxDirectMemorySize=1g -XX:+UseG1GC -Dserver.host=localhost -Dserver.port=8080 -Dbenchmark.output=dubbo-triple_output.md
# Warmup: 3 iterations, 10 s each
# Measurement: 3 iterations, 10 s each
# Timeout: 10 min per iteration
# Threads: 32 threads, will synchronize iterations
# Benchmark mode: Throughput, ops/time
# Benchmark: org.apache.dubbo.benchmark.ClientPb.existUser

# Run progress: 8.33% complete, ETA 00:12:02
# Fork: 1 of 1
# Warmup Iteration   1: 2.293 ops/ms
# Warmup Iteration   2: 7.614 ops/ms
# Warmup Iteration   3: 8.070 ops/ms
Iteration   1: 8.441 ops/ms
Iteration   2: 8.222 ops/ms
Iteration   3: 8.419 ops/ms


Result "org.apache.dubbo.benchmark.ClientPb.existUser":
  8.361 ±(99.9%) 2.199 ops/ms [Average]
  (min, avg, max) = (8.222, 8.361, 8.441), stdev = 0.121
  CI (99.9%): [6.162, 10.560] (assumes normal distribution)


# JMH version: 1.21
# VM version: JDK 1.8.0_372, OpenJDK 64-Bit Server VM, 25.372-b07
# VM invoker: /opt/hostedtoolcache/Java_Adopt_jdk/8.0.372-7/x64/jre/bin/java
# VM options: -Xmx1g -Xms1g -XX:MaxDirectMemorySize=1g -XX:+UseG1GC -Dserver.host=localhost -Dserver.port=8080 -Dbenchmark.output=dubbo-triple_output.md
# Warmup: 3 iterations, 10 s each
# Measurement: 3 iterations, 10 s each
# Timeout: 10 min per iteration
# Threads: 32 threads, will synchronize iterations
# Benchmark mode: Throughput, ops/time
# Benchmark: org.apache.dubbo.benchmark.ClientPb.getUser

# Run progress: 16.67% complete, ETA 00:11:00
# Fork: 1 of 1
# Warmup Iteration   1: 2.321 ops/ms
# Warmup Iteration   2: 6.554 ops/ms
# Warmup Iteration   3: 8.076 ops/ms
Iteration   1: 7.996 ops/ms
Iteration   2: 8.004 ops/ms
Iteration   3: 7.976 ops/ms


Result "org.apache.dubbo.benchmark.ClientPb.getUser":
  7.992 ±(99.9%) 0.271 ops/ms [Average]
  (min, avg, max) = (7.976, 7.992, 8.004), stdev = 0.015
  CI (99.9%): [7.721, 8.263] (assumes normal distribution)


# JMH version: 1.21
# VM version: JDK 1.8.0_372, OpenJDK 64-Bit Server VM, 25.372-b07
# VM invoker: /opt/hostedtoolcache/Java_Adopt_jdk/8.0.372-7/x64/jre/bin/java
# VM options: -Xmx1g -Xms1g -XX:MaxDirectMemorySize=1g -XX:+UseG1GC -Dserver.host=localhost -Dserver.port=8080 -Dbenchmark.output=dubbo-triple_output.md
# Warmup: 3 iterations, 10 s each
# Measurement: 3 iterations, 10 s each
# Timeout: 10 min per iteration
# Threads: 32 threads, will synchronize iterations
# Benchmark mode: Throughput, ops/time
# Benchmark: org.apache.dubbo.benchmark.ClientPb.listUser

# Run progress: 25.00% complete, ETA 00:09:52
# Fork: 1 of 1
# Warmup Iteration   1: 1.811 ops/ms
# Warmup Iteration   2: 5.454 ops/ms
# Warmup Iteration   3: 6.594 ops/ms
Iteration   1: 6.777 ops/ms
Iteration   2: 6.448 ops/ms
Iteration   3: 6.535 ops/ms


Result "org.apache.dubbo.benchmark.ClientPb.listUser":
  6.586 ±(99.9%) 3.105 ops/ms [Average]
  (min, avg, max) = (6.448, 6.586, 6.777), stdev = 0.170
  CI (99.9%): [3.481, 9.692] (assumes normal distribution)


# JMH version: 1.21
# VM version: JDK 1.8.0_372, OpenJDK 64-Bit Server VM, 25.372-b07
# VM invoker: /opt/hostedtoolcache/Java_Adopt_jdk/8.0.372-7/x64/jre/bin/java
# VM options: -Xmx1g -Xms1g -XX:MaxDirectMemorySize=1g -XX:+UseG1GC -Dserver.host=localhost -Dserver.port=8080 -Dbenchmark.output=dubbo-triple_output.md
# Warmup: 3 iterations, 10 s each
# Measurement: 3 iterations, 10 s each
# Timeout: 10 min per iteration
# Threads: 32 threads, will synchronize iterations
# Benchmark mode: Average time, time/op
# Benchmark: org.apache.dubbo.benchmark.ClientPb.createUser

# Run progress: 33.33% complete, ETA 00:08:48
# Fork: 1 of 1
# Warmup Iteration   1: 9.725 ±(99.9%) 0.054 ms/op
# Warmup Iteration   2: 5.360 ±(99.9%) 0.005 ms/op
# Warmup Iteration   3: 4.195 ±(99.9%) 0.012 ms/op
Iteration   1: 4.005 ±(99.9%) 0.009 ms/op
Iteration   2: 3.991 ±(99.9%) 0.007 ms/op
Iteration   3: 3.899 ±(99.9%) 0.014 ms/op


Result "org.apache.dubbo.benchmark.ClientPb.createUser":
  3.965 ±(99.9%) 1.053 ms/op [Average]
  (min, avg, max) = (3.899, 3.965, 4.005), stdev = 0.058
  CI (99.9%): [2.911, 5.018] (assumes normal distribution)


# JMH version: 1.21
# VM version: JDK 1.8.0_372, OpenJDK 64-Bit Server VM, 25.372-b07
# VM invoker: /opt/hostedtoolcache/Java_Adopt_jdk/8.0.372-7/x64/jre/bin/java
# VM options: -Xmx1g -Xms1g -XX:MaxDirectMemorySize=1g -XX:+UseG1GC -Dserver.host=localhost -Dserver.port=8080 -Dbenchmark.output=dubbo-triple_output.md
# Warmup: 3 iterations, 10 s each
# Measurement: 3 iterations, 10 s each
# Timeout: 10 min per iteration
# Threads: 32 threads, will synchronize iterations
# Benchmark mode: Average time, time/op
# Benchmark: org.apache.dubbo.benchmark.ClientPb.existUser

# Run progress: 41.67% complete, ETA 00:07:41
# Fork: 1 of 1
# Warmup Iteration   1: 11.371 ±(99.9%) 0.030 ms/op
# Warmup Iteration   2: 4.189 ±(99.9%) 0.008 ms/op
# Warmup Iteration   3: 3.997 ±(99.9%) 0.008 ms/op
Iteration   1: 3.958 ±(99.9%) 0.008 ms/op
Iteration   2: 3.772 ±(99.9%) 0.004 ms/op
Iteration   3: 3.812 ±(99.9%) 0.014 ms/op


Result "org.apache.dubbo.benchmark.ClientPb.existUser":
  3.847 ±(99.9%) 1.779 ms/op [Average]
  (min, avg, max) = (3.772, 3.847, 3.958), stdev = 0.098
  CI (99.9%): [2.068, 5.627] (assumes normal distribution)


# JMH version: 1.21
# VM version: JDK 1.8.0_372, OpenJDK 64-Bit Server VM, 25.372-b07
# VM invoker: /opt/hostedtoolcache/Java_Adopt_jdk/8.0.372-7/x64/jre/bin/java
# VM options: -Xmx1g -Xms1g -XX:MaxDirectMemorySize=1g -XX:+UseG1GC -Dserver.host=localhost -Dserver.port=8080 -Dbenchmark.output=dubbo-triple_output.md
# Warmup: 3 iterations, 10 s each
# Measurement: 3 iterations, 10 s each
# Timeout: 10 min per iteration
# Threads: 32 threads, will synchronize iterations
# Benchmark mode: Average time, time/op
# Benchmark: org.apache.dubbo.benchmark.ClientPb.getUser

# Run progress: 50.00% complete, ETA 00:06:35
# Fork: 1 of 1
# Warmup Iteration   1: 13.395 ±(99.9%) 0.041 ms/op
# Warmup Iteration   2: 4.648 ±(99.9%) 0.005 ms/op
# Warmup Iteration   3: 4.359 ±(99.9%) 0.008 ms/op
Iteration   1: 3.966 ±(99.9%) 0.006 ms/op
Iteration   2: 3.945 ±(99.9%) 0.006 ms/op
Iteration   3: 3.899 ±(99.9%) 0.018 ms/op


Result "org.apache.dubbo.benchmark.ClientPb.getUser":
  3.937 ±(99.9%) 0.628 ms/op [Average]
  (min, avg, max) = (3.899, 3.937, 3.966), stdev = 0.034
  CI (99.9%): [3.309, 4.564] (assumes normal distribution)


# JMH version: 1.21
# VM version: JDK 1.8.0_372, OpenJDK 64-Bit Server VM, 25.372-b07
# VM invoker: /opt/hostedtoolcache/Java_Adopt_jdk/8.0.372-7/x64/jre/bin/java
# VM options: -Xmx1g -Xms1g -XX:MaxDirectMemorySize=1g -XX:+UseG1GC -Dserver.host=localhost -Dserver.port=8080 -Dbenchmark.output=dubbo-triple_output.md
# Warmup: 3 iterations, 10 s each
# Measurement: 3 iterations, 10 s each
# Timeout: 10 min per iteration
# Threads: 32 threads, will synchronize iterations
# Benchmark mode: Average time, time/op
# Benchmark: org.apache.dubbo.benchmark.ClientPb.listUser

# Run progress: 58.33% complete, ETA 00:05:29
# Fork: 1 of 1
# Warmup Iteration   1: 14.353 ±(99.9%) 0.048 ms/op
# Warmup Iteration   2: 5.669 ±(99.9%) 0.005 ms/op
# Warmup Iteration   3: 4.966 ±(99.9%) 0.005 ms/op
Iteration   1: 4.559 ±(99.9%) 0.017 ms/op
Iteration   2: 4.496 ±(99.9%) 0.013 ms/op
Iteration   3: 4.886 ±(99.9%) 0.012 ms/op


Result "org.apache.dubbo.benchmark.ClientPb.listUser":
  4.647 ±(99.9%) 3.823 ms/op [Average]
  (min, avg, max) = (4.496, 4.647, 4.886), stdev = 0.210
  CI (99.9%): [0.825, 8.470] (assumes normal distribution)


# JMH version: 1.21
# VM version: JDK 1.8.0_372, OpenJDK 64-Bit Server VM, 25.372-b07
# VM invoker: /opt/hostedtoolcache/Java_Adopt_jdk/8.0.372-7/x64/jre/bin/java
# VM options: -Xmx1g -Xms1g -XX:MaxDirectMemorySize=1g -XX:+UseG1GC -Dserver.host=localhost -Dserver.port=8080 -Dbenchmark.output=dubbo-triple_output.md
# Warmup: 3 iterations, 10 s each
# Measurement: 3 iterations, 10 s each
# Timeout: 10 min per iteration
# Threads: 32 threads, will synchronize iterations
# Benchmark mode: Sampling time
# Benchmark: org.apache.dubbo.benchmark.ClientPb.createUser

# Run progress: 66.67% complete, ETA 00:04:23
# Fork: 1 of 1
# Warmup Iteration   1: 12.774 ±(99.9%) 0.160 ms/op
# Warmup Iteration   2: 5.210 ±(99.9%) 0.029 ms/op
# Warmup Iteration   3: 4.452 ±(99.9%) 0.019 ms/op
Iteration   1: 3.957 ±(99.9%) 0.010 ms/op
                 createUser·p0.00:   2.066 ms/op
                 createUser·p0.50:   3.777 ms/op
                 createUser·p0.90:   4.481 ms/op
                 createUser·p0.95:   4.866 ms/op
                 createUser·p0.99:   7.094 ms/op
                 createUser·p0.999:  14.270 ms/op
                 createUser·p0.9999: 24.803 ms/op
                 createUser·p1.00:   26.903 ms/op

Iteration   2: 4.007 ±(99.9%) 0.013 ms/op
                 createUser·p0.00:   1.874 ms/op
                 createUser·p0.50:   3.940 ms/op
                 createUser·p0.90:   4.358 ms/op
                 createUser·p0.95:   4.809 ms/op
                 createUser·p0.99:   6.597 ms/op
                 createUser·p0.999:  24.674 ms/op
                 createUser·p0.9999: 27.460 ms/op
                 createUser·p1.00:   28.246 ms/op

Iteration   3: 4.054 ±(99.9%) 0.013 ms/op
                 createUser·p0.00:   1.364 ms/op
                 createUser·p0.50:   3.813 ms/op
                 createUser·p0.90:   4.653 ms/op
                 createUser·p0.95:   5.587 ms/op
                 createUser·p0.99:   8.020 ms/op
                 createUser·p0.999:  16.941 ms/op
                 createUser·p0.9999: 29.396 ms/op
                 createUser·p1.00:   30.474 ms/op



Result "org.apache.dubbo.benchmark.ClientPb.createUser":
  N = 239693
  mean =      4.006 ±(99.9%) 0.007 ms/op

  Histogram, ms/op:
    [ 0.000,  2.500) = 234 
    [ 2.500,  5.000) = 227363 
    [ 5.000,  7.500) = 10095 
    [ 7.500, 10.000) = 1327 
    [10.000, 12.500) = 220 
    [12.500, 15.000) = 131 
    [15.000, 17.500) = 87 
    [17.500, 20.000) = 12 
    [20.000, 22.500) = 0 
    [22.500, 25.000) = 92 
    [25.000, 27.500) = 82 
    [27.500, 30.000) = 47 
    [30.000, 32.500) = 3 
    [32.500, 35.000) = 0 
    [35.000, 37.500) = 0 

  Percentiles, ms/op:
      p(0.0000) =      1.364 ms/op
     p(50.0000) =      3.863 ms/op
     p(90.0000) =      4.506 ms/op
     p(95.0000) =      5.014 ms/op
     p(99.0000) =      7.176 ms/op
     p(99.9000) =     17.433 ms/op
     p(99.9900) =     28.641 ms/op
     p(99.9990) =     30.199 ms/op
     p(99.9999) =     30.474 ms/op
    p(100.0000) =     30.474 ms/op


# JMH version: 1.21
# VM version: JDK 1.8.0_372, OpenJDK 64-Bit Server VM, 25.372-b07
# VM invoker: /opt/hostedtoolcache/Java_Adopt_jdk/8.0.372-7/x64/jre/bin/java
# VM options: -Xmx1g -Xms1g -XX:MaxDirectMemorySize=1g -XX:+UseG1GC -Dserver.host=localhost -Dserver.port=8080 -Dbenchmark.output=dubbo-triple_output.md
# Warmup: 3 iterations, 10 s each
# Measurement: 3 iterations, 10 s each
# Timeout: 10 min per iteration
# Threads: 32 threads, will synchronize iterations
# Benchmark mode: Sampling time
# Benchmark: org.apache.dubbo.benchmark.ClientPb.existUser

# Run progress: 75.00% complete, ETA 00:03:18
# Fork: 1 of 1
# Warmup Iteration   1: 12.275 ±(99.9%) 0.156 ms/op
# Warmup Iteration   2: 4.466 ±(99.9%) 0.019 ms/op
# Warmup Iteration   3: 3.760 ±(99.9%) 0.009 ms/op
Iteration   1: 3.732 ±(99.9%) 0.010 ms/op
                 existUser·p0.00:   1.872 ms/op
                 existUser·p0.50:   3.592 ms/op
                 existUser·p0.90:   4.043 ms/op
                 existUser·p0.95:   4.284 ms/op
                 existUser·p0.99:   6.626 ms/op
                 existUser·p0.999:  22.092 ms/op
                 existUser·p0.9999: 26.242 ms/op
                 existUser·p1.00:   27.230 ms/op

Iteration   2: 3.878 ±(99.9%) 0.011 ms/op
                 existUser·p0.00:   1.731 ms/op
                 existUser·p0.50:   3.740 ms/op
                 existUser·p0.90:   4.366 ms/op
                 existUser·p0.95:   4.858 ms/op
                 existUser·p0.99:   7.348 ms/op
                 existUser·p0.999:  11.600 ms/op
                 existUser·p0.9999: 26.329 ms/op
                 existUser·p1.00:   26.608 ms/op

Iteration   3: 3.804 ±(99.9%) 0.010 ms/op
                 existUser·p0.00:   1.815 ms/op
                 existUser·p0.50:   3.731 ms/op
                 existUser·p0.90:   4.301 ms/op
                 existUser·p0.95:   4.579 ms/op
                 existUser·p0.99:   5.849 ms/op
                 existUser·p0.999:  14.237 ms/op
                 existUser·p0.9999: 30.966 ms/op
                 existUser·p1.00:   32.244 ms/op



Result "org.apache.dubbo.benchmark.ClientPb.existUser":
  N = 252384
  mean =      3.804 ±(99.9%) 0.006 ms/op

  Histogram, ms/op:
    [ 0.000,  2.500) = 232 
    [ 2.500,  5.000) = 244369 
    [ 5.000,  7.500) = 6265 
    [ 7.500, 10.000) = 992 
    [10.000, 12.500) = 230 
    [12.500, 15.000) = 53 
    [15.000, 17.500) = 19 
    [17.500, 20.000) = 0 
    [20.000, 22.500) = 13 
    [22.500, 25.000) = 96 
    [25.000, 27.500) = 83 
    [27.500, 30.000) = 20 
    [30.000, 32.500) = 12 
    [32.500, 35.000) = 0 
    [35.000, 37.500) = 0 

  Percentiles, ms/op:
      p(0.0000) =      1.731 ms/op
     p(50.0000) =      3.682 ms/op
     p(90.0000) =      4.227 ms/op
     p(95.0000) =      4.604 ms/op
     p(99.0000) =      6.767 ms/op
     p(99.9000) =     14.051 ms/op
     p(99.9900) =     28.525 ms/op
     p(99.9990) =     32.077 ms/op
     p(99.9999) =     32.244 ms/op
    p(100.0000) =     32.244 ms/op


# JMH version: 1.21
# VM version: JDK 1.8.0_372, OpenJDK 64-Bit Server VM, 25.372-b07
# VM invoker: /opt/hostedtoolcache/Java_Adopt_jdk/8.0.372-7/x64/jre/bin/java
# VM options: -Xmx1g -Xms1g -XX:MaxDirectMemorySize=1g -XX:+UseG1GC -Dserver.host=localhost -Dserver.port=8080 -Dbenchmark.output=dubbo-triple_output.md
# Warmup: 3 iterations, 10 s each
# Measurement: 3 iterations, 10 s each
# Timeout: 10 min per iteration
# Threads: 32 threads, will synchronize iterations
# Benchmark mode: Sampling time
# Benchmark: org.apache.dubbo.benchmark.ClientPb.getUser

# Run progress: 83.33% complete, ETA 00:02:12
# Fork: 1 of 1
# Warmup Iteration   1: 13.205 ±(99.9%) 0.172 ms/op
# Warmup Iteration   2: 4.574 ±(99.9%) 0.020 ms/op
# Warmup Iteration   3: 4.271 ±(99.9%) 0.013 ms/op
Iteration   1: 4.193 ±(99.9%) 0.016 ms/op
                 getUser·p0.00:   1.737 ms/op
                 getUser·p0.50:   3.924 ms/op
                 getUser·p0.90:   4.907 ms/op
                 getUser·p0.95:   6.300 ms/op
                 getUser·p0.99:   8.929 ms/op
                 getUser·p0.999:  22.249 ms/op
                 getUser·p0.9999: 33.554 ms/op
                 getUser·p1.00:   33.554 ms/op

Iteration   2: 3.935 ±(99.9%) 0.009 ms/op
                 getUser·p0.00:   2.138 ms/op
                 getUser·p0.50:   3.826 ms/op
                 getUser·p0.90:   4.325 ms/op
                 getUser·p0.95:   4.555 ms/op
                 getUser·p0.99:   6.570 ms/op
                 getUser·p0.999:  10.224 ms/op
                 getUser·p0.9999: 26.071 ms/op
                 getUser·p1.00:   27.558 ms/op

Iteration   3: 3.867 ±(99.9%) 0.011 ms/op
                 getUser·p0.00:   2.220 ms/op
                 getUser·p0.50:   3.756 ms/op
                 getUser·p0.90:   4.243 ms/op
                 getUser·p0.95:   4.604 ms/op
                 getUser·p0.99:   6.562 ms/op
                 getUser·p0.999:  23.897 ms/op
                 getUser·p0.9999: 26.271 ms/op
                 getUser·p1.00:   27.230 ms/op



Result "org.apache.dubbo.benchmark.ClientPb.getUser":
  N = 240371
  mean =      3.994 ±(99.9%) 0.007 ms/op

  Histogram, ms/op:
    [ 0.000,  2.500) = 49 
    [ 2.500,  5.000) = 228385 
    [ 5.000,  7.500) = 9291 
    [ 7.500, 10.000) = 1792 
    [10.000, 12.500) = 480 
    [12.500, 15.000) = 105 
    [15.000, 17.500) = 8 
    [17.500, 20.000) = 5 
    [20.000, 22.500) = 28 
    [22.500, 25.000) = 139 
    [25.000, 27.500) = 55 
    [27.500, 30.000) = 5 
    [30.000, 32.500) = 2 
    [32.500, 35.000) = 27 
    [35.000, 37.500) = 0 

  Percentiles, ms/op:
      p(0.0000) =      1.737 ms/op
     p(50.0000) =      3.830 ms/op
     p(90.0000) =      4.456 ms/op
     p(95.0000) =      4.989 ms/op
     p(99.0000) =      7.635 ms/op
     p(99.9000) =     22.073 ms/op
     p(99.9900) =     33.325 ms/op
     p(99.9990) =     33.554 ms/op
     p(99.9999) =     33.554 ms/op
    p(100.0000) =     33.554 ms/op


# JMH version: 1.21
# VM version: JDK 1.8.0_372, OpenJDK 64-Bit Server VM, 25.372-b07
# VM invoker: /opt/hostedtoolcache/Java_Adopt_jdk/8.0.372-7/x64/jre/bin/java
# VM options: -Xmx1g -Xms1g -XX:MaxDirectMemorySize=1g -XX:+UseG1GC -Dserver.host=localhost -Dserver.port=8080 -Dbenchmark.output=dubbo-triple_output.md
# Warmup: 3 iterations, 10 s each
# Measurement: 3 iterations, 10 s each
# Timeout: 10 min per iteration
# Threads: 32 threads, will synchronize iterations
# Benchmark mode: Sampling time
# Benchmark: org.apache.dubbo.benchmark.ClientPb.listUser

# Run progress: 91.67% complete, ETA 00:01:06
# Fork: 1 of 1
# Warmup Iteration   1: 14.906 ±(99.9%) 0.213 ms/op
# Warmup Iteration   2: 5.194 ±(99.9%) 0.023 ms/op
# Warmup Iteration   3: 4.858 ±(99.9%) 0.018 ms/op
Iteration   1: 4.639 ±(99.9%) 0.015 ms/op
                 listUser·p0.00:   1.868 ms/op
                 listUser·p0.50:   4.407 ms/op
                 listUser·p0.90:   5.095 ms/op
                 listUser·p0.95:   5.612 ms/op
                 listUser·p0.99:   8.583 ms/op
                 listUser·p0.999:  24.773 ms/op
                 listUser·p0.9999: 28.188 ms/op
                 listUser·p1.00:   29.622 ms/op

Iteration   2: 4.628 ±(99.9%) 0.012 ms/op
                 listUser·p0.00:   2.257 ms/op
                 listUser·p0.50:   4.456 ms/op
                 listUser·p0.90:   5.120 ms/op
                 listUser·p0.95:   5.513 ms/op
                 listUser·p0.99:   8.733 ms/op
                 listUser·p0.999:  17.564 ms/op
                 listUser·p0.9999: 21.119 ms/op
                 listUser·p1.00:   21.627 ms/op

Iteration   3: 4.545 ±(99.9%) 0.012 ms/op
                 listUser·p0.00:   2.572 ms/op
                 listUser·p0.50:   4.456 ms/op
                 listUser·p0.90:   4.792 ms/op
                 listUser·p0.95:   5.095 ms/op
                 listUser·p0.99:   8.315 ms/op
                 listUser·p0.999:  17.203 ms/op
                 listUser·p0.9999: 18.219 ms/op
                 listUser·p1.00:   18.317 ms/op



Result "org.apache.dubbo.benchmark.ClientPb.listUser":
  N = 208238
  mean =      4.604 ±(99.9%) 0.008 ms/op

  Histogram, ms/op:
    [ 0.000,  2.500) = 11 
    [ 2.500,  5.000) = 187056 
    [ 5.000,  7.500) = 17027 
    [ 7.500, 10.000) = 2950 
    [10.000, 12.500) = 543 
    [12.500, 15.000) = 224 
    [15.000, 17.500) = 187 
    [17.500, 20.000) = 98 
    [20.000, 22.500) = 15 
    [22.500, 25.000) = 64 
    [25.000, 27.500) = 52 

  Percentiles, ms/op:
      p(0.0000) =      1.868 ms/op
     p(50.0000) =      4.440 ms/op
     p(90.0000) =      5.005 ms/op
     p(95.0000) =      5.431 ms/op
     p(99.0000) =      8.552 ms/op
     p(99.9000) =     17.859 ms/op
     p(99.9900) =     26.827 ms/op
     p(99.9990) =     29.590 ms/op
     p(99.9999) =     29.622 ms/op
    p(100.0000) =     29.622 ms/op


# Run complete. Total time: 00:13:15

REMEMBER: The numbers below are just data. To gain reusable insights, you need to follow up on
why the numbers are the way they are. Use profilers (see -prof, -lprof), design factorial
experiments, perform baseline and negative tests that provide experimental control, make sure
the benchmarking environment is safe on JVM/OS/HW level, ask for reviews from the domain experts.
Do not assume the numbers tell you what you want them to tell.

Benchmark                                 Mode     Cnt   Score   Error   Units
ClientPb.createUser                      thrpt       3   7.730 ± 4.062  ops/ms
ClientPb.existUser                       thrpt       3   8.361 ± 2.199  ops/ms
ClientPb.getUser                         thrpt       3   7.992 ± 0.271  ops/ms
ClientPb.listUser                        thrpt       3   6.586 ± 3.105  ops/ms
ClientPb.createUser                       avgt       3   3.965 ± 1.053   ms/op
ClientPb.existUser                        avgt       3   3.847 ± 1.779   ms/op
ClientPb.getUser                          avgt       3   3.937 ± 0.628   ms/op
ClientPb.listUser                         avgt       3   4.647 ± 3.823   ms/op
ClientPb.createUser                     sample  239693   4.006 ± 0.007   ms/op
ClientPb.createUser:createUser·p0.00    sample           1.364           ms/op
ClientPb.createUser:createUser·p0.50    sample           3.863           ms/op
ClientPb.createUser:createUser·p0.90    sample           4.506           ms/op
ClientPb.createUser:createUser·p0.95    sample           5.014           ms/op
ClientPb.createUser:createUser·p0.99    sample           7.176           ms/op
ClientPb.createUser:createUser·p0.999   sample          17.433           ms/op
ClientPb.createUser:createUser·p0.9999  sample          28.641           ms/op
ClientPb.createUser:createUser·p1.00    sample          30.474           ms/op
ClientPb.existUser                      sample  252384   3.804 ± 0.006   ms/op
ClientPb.existUser:existUser·p0.00      sample           1.731           ms/op
ClientPb.existUser:existUser·p0.50      sample           3.682           ms/op
ClientPb.existUser:existUser·p0.90      sample           4.227           ms/op
ClientPb.existUser:existUser·p0.95      sample           4.604           ms/op
ClientPb.existUser:existUser·p0.99      sample           6.767           ms/op
ClientPb.existUser:existUser·p0.999     sample          14.051           ms/op
ClientPb.existUser:existUser·p0.9999    sample          28.525           ms/op
ClientPb.existUser:existUser·p1.00      sample          32.244           ms/op
ClientPb.getUser                        sample  240371   3.994 ± 0.007   ms/op
ClientPb.getUser:getUser·p0.00          sample           1.737           ms/op
ClientPb.getUser:getUser·p0.50          sample           3.830           ms/op
ClientPb.getUser:getUser·p0.90          sample           4.456           ms/op
ClientPb.getUser:getUser·p0.95          sample           4.989           ms/op
ClientPb.getUser:getUser·p0.99          sample           7.635           ms/op
ClientPb.getUser:getUser·p0.999         sample          22.073           ms/op
ClientPb.getUser:getUser·p0.9999        sample          33.325           ms/op
ClientPb.getUser:getUser·p1.00          sample          33.554           ms/op
ClientPb.listUser                       sample  208238   4.604 ± 0.008   ms/op
ClientPb.listUser:listUser·p0.00        sample           1.868           ms/op
ClientPb.listUser:listUser·p0.50        sample           4.440           ms/op
ClientPb.listUser:listUser·p0.90        sample           5.005           ms/op
ClientPb.listUser:listUser·p0.95        sample           5.431           ms/op
ClientPb.listUser:listUser·p0.99        sample           8.552           ms/op
ClientPb.listUser:listUser·p0.999       sample          17.859           ms/op
ClientPb.listUser:listUser·p0.9999      sample          26.827           ms/op
ClientPb.listUser:listUser·p1.00        sample          29.622           ms/op
