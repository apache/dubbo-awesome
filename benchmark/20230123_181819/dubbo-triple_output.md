# JMH version: 1.21
# VM version: JDK 1.8.0_362, OpenJDK 64-Bit Server VM, 25.362-b09
# VM invoker: /opt/hostedtoolcache/Java_Adopt_jdk/8.0.362-9/x64/jre/bin/java
# VM options: -Xmx1g -Xms1g -XX:MaxDirectMemorySize=1g -XX:+UseG1GC -Dserver.host=localhost -Dserver.port=8080 -Dbenchmark.output=dubbo-triple_output.md
# Warmup: 3 iterations, 10 s each
# Measurement: 3 iterations, 10 s each
# Timeout: 10 min per iteration
# Threads: 32 threads, will synchronize iterations
# Benchmark mode: Throughput, ops/time
# Benchmark: org.apache.dubbo.benchmark.ClientPb.createUser

# Run progress: 0.00% complete, ETA 00:12:00
# Fork: 1 of 1
# Warmup Iteration   1: 1.912 ops/ms
# Warmup Iteration   2: 5.718 ops/ms
# Warmup Iteration   3: 9.114 ops/ms
Iteration   1: 9.979 ops/ms
Iteration   2: 9.852 ops/ms
Iteration   3: 10.187 ops/ms


Result "org.apache.dubbo.benchmark.ClientPb.createUser":
  10.006 ±(99.9%) 3.084 ops/ms [Average]
  (min, avg, max) = (9.852, 10.006, 10.187), stdev = 0.169
  CI (99.9%): [6.923, 13.090] (assumes normal distribution)


# JMH version: 1.21
# VM version: JDK 1.8.0_362, OpenJDK 64-Bit Server VM, 25.362-b09
# VM invoker: /opt/hostedtoolcache/Java_Adopt_jdk/8.0.362-9/x64/jre/bin/java
# VM options: -Xmx1g -Xms1g -XX:MaxDirectMemorySize=1g -XX:+UseG1GC -Dserver.host=localhost -Dserver.port=8080 -Dbenchmark.output=dubbo-triple_output.md
# Warmup: 3 iterations, 10 s each
# Measurement: 3 iterations, 10 s each
# Timeout: 10 min per iteration
# Threads: 32 threads, will synchronize iterations
# Benchmark mode: Throughput, ops/time
# Benchmark: org.apache.dubbo.benchmark.ClientPb.existUser

# Run progress: 8.33% complete, ETA 00:12:08
# Fork: 1 of 1
# Warmup Iteration   1: 2.975 ops/ms
# Warmup Iteration   2: 8.472 ops/ms
# Warmup Iteration   3: 9.154 ops/ms
Iteration   1: 9.376 ops/ms
Iteration   2: 9.625 ops/ms
Iteration   3: 9.651 ops/ms


Result "org.apache.dubbo.benchmark.ClientPb.existUser":
  9.550 ±(99.9%) 2.769 ops/ms [Average]
  (min, avg, max) = (9.376, 9.550, 9.651), stdev = 0.152
  CI (99.9%): [6.782, 12.319] (assumes normal distribution)


# JMH version: 1.21
# VM version: JDK 1.8.0_362, OpenJDK 64-Bit Server VM, 25.362-b09
# VM invoker: /opt/hostedtoolcache/Java_Adopt_jdk/8.0.362-9/x64/jre/bin/java
# VM options: -Xmx1g -Xms1g -XX:MaxDirectMemorySize=1g -XX:+UseG1GC -Dserver.host=localhost -Dserver.port=8080 -Dbenchmark.output=dubbo-triple_output.md
# Warmup: 3 iterations, 10 s each
# Measurement: 3 iterations, 10 s each
# Timeout: 10 min per iteration
# Threads: 32 threads, will synchronize iterations
# Benchmark mode: Throughput, ops/time
# Benchmark: org.apache.dubbo.benchmark.ClientPb.getUser

# Run progress: 16.67% complete, ETA 00:11:01
# Fork: 1 of 1
# Warmup Iteration   1: 2.684 ops/ms
# Warmup Iteration   2: 8.062 ops/ms
# Warmup Iteration   3: 9.018 ops/ms
Iteration   1: 9.348 ops/ms
Iteration   2: 9.284 ops/ms
Iteration   3: 8.882 ops/ms


Result "org.apache.dubbo.benchmark.ClientPb.getUser":
  9.172 ±(99.9%) 4.610 ops/ms [Average]
  (min, avg, max) = (8.882, 9.172, 9.348), stdev = 0.253
  CI (99.9%): [4.562, 13.782] (assumes normal distribution)


# JMH version: 1.21
# VM version: JDK 1.8.0_362, OpenJDK 64-Bit Server VM, 25.362-b09
# VM invoker: /opt/hostedtoolcache/Java_Adopt_jdk/8.0.362-9/x64/jre/bin/java
# VM options: -Xmx1g -Xms1g -XX:MaxDirectMemorySize=1g -XX:+UseG1GC -Dserver.host=localhost -Dserver.port=8080 -Dbenchmark.output=dubbo-triple_output.md
# Warmup: 3 iterations, 10 s each
# Measurement: 3 iterations, 10 s each
# Timeout: 10 min per iteration
# Threads: 32 threads, will synchronize iterations
# Benchmark mode: Throughput, ops/time
# Benchmark: org.apache.dubbo.benchmark.ClientPb.listUser

# Run progress: 25.00% complete, ETA 00:09:55
# Fork: 1 of 1
# Warmup Iteration   1: 2.896 ops/ms
# Warmup Iteration   2: 7.604 ops/ms
# Warmup Iteration   3: 8.251 ops/ms
Iteration   1: 8.248 ops/ms
Iteration   2: 8.294 ops/ms
Iteration   3: 8.325 ops/ms


Result "org.apache.dubbo.benchmark.ClientPb.listUser":
  8.289 ±(99.9%) 0.708 ops/ms [Average]
  (min, avg, max) = (8.248, 8.289, 8.325), stdev = 0.039
  CI (99.9%): [7.581, 8.998] (assumes normal distribution)


# JMH version: 1.21
# VM version: JDK 1.8.0_362, OpenJDK 64-Bit Server VM, 25.362-b09
# VM invoker: /opt/hostedtoolcache/Java_Adopt_jdk/8.0.362-9/x64/jre/bin/java
# VM options: -Xmx1g -Xms1g -XX:MaxDirectMemorySize=1g -XX:+UseG1GC -Dserver.host=localhost -Dserver.port=8080 -Dbenchmark.output=dubbo-triple_output.md
# Warmup: 3 iterations, 10 s each
# Measurement: 3 iterations, 10 s each
# Timeout: 10 min per iteration
# Threads: 32 threads, will synchronize iterations
# Benchmark mode: Average time, time/op
# Benchmark: org.apache.dubbo.benchmark.ClientPb.createUser

# Run progress: 33.33% complete, ETA 00:08:47
# Fork: 1 of 1
# Warmup Iteration   1: 9.155 ±(99.9%) 0.035 ms/op
# Warmup Iteration   2: 3.636 ±(99.9%) 0.003 ms/op
# Warmup Iteration   3: 3.526 ±(99.9%) 0.003 ms/op
Iteration   1: 3.482 ±(99.9%) 0.003 ms/op
Iteration   2: 3.333 ±(99.9%) 0.004 ms/op
Iteration   3: 3.323 ±(99.9%) 0.004 ms/op


Result "org.apache.dubbo.benchmark.ClientPb.createUser":
  3.379 ±(99.9%) 1.630 ms/op [Average]
  (min, avg, max) = (3.323, 3.379, 3.482), stdev = 0.089
  CI (99.9%): [1.750, 5.009] (assumes normal distribution)


# JMH version: 1.21
# VM version: JDK 1.8.0_362, OpenJDK 64-Bit Server VM, 25.362-b09
# VM invoker: /opt/hostedtoolcache/Java_Adopt_jdk/8.0.362-9/x64/jre/bin/java
# VM options: -Xmx1g -Xms1g -XX:MaxDirectMemorySize=1g -XX:+UseG1GC -Dserver.host=localhost -Dserver.port=8080 -Dbenchmark.output=dubbo-triple_output.md
# Warmup: 3 iterations, 10 s each
# Measurement: 3 iterations, 10 s each
# Timeout: 10 min per iteration
# Threads: 32 threads, will synchronize iterations
# Benchmark mode: Average time, time/op
# Benchmark: org.apache.dubbo.benchmark.ClientPb.existUser

# Run progress: 41.67% complete, ETA 00:07:40
# Fork: 1 of 1
# Warmup Iteration   1: 8.904 ±(99.9%) 0.035 ms/op
# Warmup Iteration   2: 3.469 ±(99.9%) 0.013 ms/op
# Warmup Iteration   3: 3.240 ±(99.9%) 0.007 ms/op
Iteration   1: 3.178 ±(99.9%) 0.008 ms/op
Iteration   2: 3.129 ±(99.9%) 0.006 ms/op
Iteration   3: 3.037 ±(99.9%) 0.006 ms/op


Result "org.apache.dubbo.benchmark.ClientPb.existUser":
  3.114 ±(99.9%) 1.302 ms/op [Average]
  (min, avg, max) = (3.037, 3.114, 3.178), stdev = 0.071
  CI (99.9%): [1.812, 4.417] (assumes normal distribution)


# JMH version: 1.21
# VM version: JDK 1.8.0_362, OpenJDK 64-Bit Server VM, 25.362-b09
# VM invoker: /opt/hostedtoolcache/Java_Adopt_jdk/8.0.362-9/x64/jre/bin/java
# VM options: -Xmx1g -Xms1g -XX:MaxDirectMemorySize=1g -XX:+UseG1GC -Dserver.host=localhost -Dserver.port=8080 -Dbenchmark.output=dubbo-triple_output.md
# Warmup: 3 iterations, 10 s each
# Measurement: 3 iterations, 10 s each
# Timeout: 10 min per iteration
# Threads: 32 threads, will synchronize iterations
# Benchmark mode: Average time, time/op
# Benchmark: org.apache.dubbo.benchmark.ClientPb.getUser

# Run progress: 50.00% complete, ETA 00:06:34
# Fork: 1 of 1
# Warmup Iteration   1: 10.228 ±(99.9%) 0.040 ms/op
# Warmup Iteration   2: 3.443 ±(99.9%) 0.007 ms/op
# Warmup Iteration   3: 3.352 ±(99.9%) 0.006 ms/op
Iteration   1: 3.258 ±(99.9%) 0.005 ms/op
Iteration   2: 3.291 ±(99.9%) 0.006 ms/op
Iteration   3: 3.479 ±(99.9%) 0.004 ms/op


Result "org.apache.dubbo.benchmark.ClientPb.getUser":
  3.343 ±(99.9%) 2.171 ms/op [Average]
  (min, avg, max) = (3.258, 3.343, 3.479), stdev = 0.119
  CI (99.9%): [1.172, 5.514] (assumes normal distribution)


# JMH version: 1.21
# VM version: JDK 1.8.0_362, OpenJDK 64-Bit Server VM, 25.362-b09
# VM invoker: /opt/hostedtoolcache/Java_Adopt_jdk/8.0.362-9/x64/jre/bin/java
# VM options: -Xmx1g -Xms1g -XX:MaxDirectMemorySize=1g -XX:+UseG1GC -Dserver.host=localhost -Dserver.port=8080 -Dbenchmark.output=dubbo-triple_output.md
# Warmup: 3 iterations, 10 s each
# Measurement: 3 iterations, 10 s each
# Timeout: 10 min per iteration
# Threads: 32 threads, will synchronize iterations
# Benchmark mode: Average time, time/op
# Benchmark: org.apache.dubbo.benchmark.ClientPb.listUser

# Run progress: 58.33% complete, ETA 00:05:29
# Fork: 1 of 1
# Warmup Iteration   1: 13.219 ±(99.9%) 0.056 ms/op
# Warmup Iteration   2: 4.595 ±(99.9%) 0.008 ms/op
# Warmup Iteration   3: 4.319 ±(99.9%) 0.008 ms/op
Iteration   1: 3.999 ±(99.9%) 0.014 ms/op
Iteration   2: 4.154 ±(99.9%) 0.014 ms/op
Iteration   3: 3.926 ±(99.9%) 0.013 ms/op


Result "org.apache.dubbo.benchmark.ClientPb.listUser":
  4.027 ±(99.9%) 2.129 ms/op [Average]
  (min, avg, max) = (3.926, 4.027, 4.154), stdev = 0.117
  CI (99.9%): [1.898, 6.155] (assumes normal distribution)


# JMH version: 1.21
# VM version: JDK 1.8.0_362, OpenJDK 64-Bit Server VM, 25.362-b09
# VM invoker: /opt/hostedtoolcache/Java_Adopt_jdk/8.0.362-9/x64/jre/bin/java
# VM options: -Xmx1g -Xms1g -XX:MaxDirectMemorySize=1g -XX:+UseG1GC -Dserver.host=localhost -Dserver.port=8080 -Dbenchmark.output=dubbo-triple_output.md
# Warmup: 3 iterations, 10 s each
# Measurement: 3 iterations, 10 s each
# Timeout: 10 min per iteration
# Threads: 32 threads, will synchronize iterations
# Benchmark mode: Sampling time
# Benchmark: org.apache.dubbo.benchmark.ClientPb.createUser

# Run progress: 66.67% complete, ETA 00:04:23
# Fork: 1 of 1
# Warmup Iteration   1: 10.107 ±(99.9%) 0.129 ms/op
# Warmup Iteration   2: 3.819 ±(99.9%) 0.018 ms/op
# Warmup Iteration   3: 3.180 ±(99.9%) 0.009 ms/op
Iteration   1: 3.066 ±(99.9%) 0.007 ms/op
                 createUser·p0.00:   1.501 ms/op
                 createUser·p0.50:   2.994 ms/op
                 createUser·p0.90:   3.305 ms/op
                 createUser·p0.95:   3.547 ms/op
                 createUser·p0.99:   5.317 ms/op
                 createUser·p0.999:  10.501 ms/op
                 createUser·p0.9999: 22.891 ms/op
                 createUser·p1.00:   23.364 ms/op

Iteration   2: 3.294 ±(99.9%) 0.011 ms/op
                 createUser·p0.00:   1.559 ms/op
                 createUser·p0.50:   3.195 ms/op
                 createUser·p0.90:   3.703 ms/op
                 createUser·p0.95:   4.162 ms/op
                 createUser·p0.99:   5.800 ms/op
                 createUser·p0.999:  15.326 ms/op
                 createUser·p0.9999: 30.516 ms/op
                 createUser·p1.00:   31.425 ms/op

Iteration   3: 3.494 ±(99.9%) 0.010 ms/op
                 createUser·p0.00:   1.159 ms/op
                 createUser·p0.50:   3.404 ms/op
                 createUser·p0.90:   3.854 ms/op
                 createUser·p0.95:   4.174 ms/op
                 createUser·p0.99:   6.390 ms/op
                 createUser·p0.999:  17.629 ms/op
                 createUser·p0.9999: 27.099 ms/op
                 createUser·p1.00:   27.886 ms/op



Result "org.apache.dubbo.benchmark.ClientPb.createUser":
  N = 292977
  mean =      3.275 ±(99.9%) 0.005 ms/op

  Histogram, ms/op:
    [ 0.000,  2.500) = 12253 
    [ 2.500,  5.000) = 274404 
    [ 5.000,  7.500) = 5194 
    [ 7.500, 10.000) = 711 
    [10.000, 12.500) = 95 
    [12.500, 15.000) = 2 
    [15.000, 17.500) = 34 
    [17.500, 20.000) = 18 
    [20.000, 22.500) = 84 
    [22.500, 25.000) = 37 
    [25.000, 27.500) = 94 
    [27.500, 30.000) = 37 
    [30.000, 32.500) = 14 
    [32.500, 35.000) = 0 
    [35.000, 37.500) = 0 

  Percentiles, ms/op:
      p(0.0000) =      1.159 ms/op
     p(50.0000) =      3.174 ms/op
     p(90.0000) =      3.670 ms/op
     p(95.0000) =      3.994 ms/op
     p(99.0000) =      5.882 ms/op
     p(99.9000) =     15.254 ms/op
     p(99.9900) =     28.443 ms/op
     p(99.9990) =     31.169 ms/op
     p(99.9999) =     31.425 ms/op
    p(100.0000) =     31.425 ms/op


# JMH version: 1.21
# VM version: JDK 1.8.0_362, OpenJDK 64-Bit Server VM, 25.362-b09
# VM invoker: /opt/hostedtoolcache/Java_Adopt_jdk/8.0.362-9/x64/jre/bin/java
# VM options: -Xmx1g -Xms1g -XX:MaxDirectMemorySize=1g -XX:+UseG1GC -Dserver.host=localhost -Dserver.port=8080 -Dbenchmark.output=dubbo-triple_output.md
# Warmup: 3 iterations, 10 s each
# Measurement: 3 iterations, 10 s each
# Timeout: 10 min per iteration
# Threads: 32 threads, will synchronize iterations
# Benchmark mode: Sampling time
# Benchmark: org.apache.dubbo.benchmark.ClientPb.existUser

# Run progress: 75.00% complete, ETA 00:03:17
# Fork: 1 of 1
# Warmup Iteration   1: 7.958 ±(99.9%) 0.100 ms/op
# Warmup Iteration   2: 3.657 ±(99.9%) 0.014 ms/op
# Warmup Iteration   3: 3.627 ±(99.9%) 0.011 ms/op
Iteration   1: 3.423 ±(99.9%) 0.009 ms/op
                 existUser·p0.00:   1.311 ms/op
                 existUser·p0.50:   3.396 ms/op
                 existUser·p0.90:   3.715 ms/op
                 existUser·p0.95:   4.084 ms/op
                 existUser·p0.99:   5.472 ms/op
                 existUser·p0.999:  21.451 ms/op
                 existUser·p0.9999: 26.695 ms/op
                 existUser·p1.00:   27.263 ms/op

Iteration   2: 3.263 ±(99.9%) 0.010 ms/op
                 existUser·p0.00:   1.591 ms/op
                 existUser·p0.50:   3.088 ms/op
                 existUser·p0.90:   3.752 ms/op
                 existUser·p0.95:   4.448 ms/op
                 existUser·p0.99:   6.461 ms/op
                 existUser·p0.999:  11.583 ms/op
                 existUser·p0.9999: 25.821 ms/op
                 existUser·p1.00:   26.968 ms/op

Iteration   3: 3.428 ±(99.9%) 0.011 ms/op
                 existUser·p0.00:   1.712 ms/op
                 existUser·p0.50:   3.334 ms/op
                 existUser·p0.90:   3.781 ms/op
                 existUser·p0.95:   4.170 ms/op
                 existUser·p0.99:   5.898 ms/op
                 existUser·p0.999:  24.379 ms/op
                 existUser·p0.9999: 30.376 ms/op
                 existUser·p1.00:   30.999 ms/op



Result "org.apache.dubbo.benchmark.ClientPb.existUser":
  N = 284733
  mean =      3.369 ±(99.9%) 0.006 ms/op

  Histogram, ms/op:
    [ 0.000,  2.500) = 12063 
    [ 2.500,  5.000) = 266708 
    [ 5.000,  7.500) = 5042 
    [ 7.500, 10.000) = 518 
    [10.000, 12.500) = 101 
    [12.500, 15.000) = 13 
    [15.000, 17.500) = 0 
    [17.500, 20.000) = 0 
    [20.000, 22.500) = 27 
    [22.500, 25.000) = 123 
    [25.000, 27.500) = 74 
    [27.500, 30.000) = 51 
    [30.000, 32.500) = 13 
    [32.500, 35.000) = 0 
    [35.000, 37.500) = 0 

  Percentiles, ms/op:
      p(0.0000) =      1.311 ms/op
     p(50.0000) =      3.326 ms/op
     p(90.0000) =      3.756 ms/op
     p(95.0000) =      4.227 ms/op
     p(99.0000) =      5.890 ms/op
     p(99.9000) =     21.498 ms/op
     p(99.9900) =     29.655 ms/op
     p(99.9990) =     30.938 ms/op
     p(99.9999) =     30.999 ms/op
    p(100.0000) =     30.999 ms/op


# JMH version: 1.21
# VM version: JDK 1.8.0_362, OpenJDK 64-Bit Server VM, 25.362-b09
# VM invoker: /opt/hostedtoolcache/Java_Adopt_jdk/8.0.362-9/x64/jre/bin/java
# VM options: -Xmx1g -Xms1g -XX:MaxDirectMemorySize=1g -XX:+UseG1GC -Dserver.host=localhost -Dserver.port=8080 -Dbenchmark.output=dubbo-triple_output.md
# Warmup: 3 iterations, 10 s each
# Measurement: 3 iterations, 10 s each
# Timeout: 10 min per iteration
# Threads: 32 threads, will synchronize iterations
# Benchmark mode: Sampling time
# Benchmark: org.apache.dubbo.benchmark.ClientPb.getUser

# Run progress: 83.33% complete, ETA 00:02:11
# Fork: 1 of 1
# Warmup Iteration   1: 8.949 ±(99.9%) 0.123 ms/op
# Warmup Iteration   2: 3.517 ±(99.9%) 0.012 ms/op
# Warmup Iteration   3: 3.225 ±(99.9%) 0.009 ms/op
Iteration   1: 3.241 ±(99.9%) 0.010 ms/op
                 getUser·p0.00:   1.233 ms/op
                 getUser·p0.50:   3.097 ms/op
                 getUser·p0.90:   3.719 ms/op
                 getUser·p0.95:   4.067 ms/op
                 getUser·p0.99:   6.504 ms/op
                 getUser·p0.999:  20.054 ms/op
                 getUser·p0.9999: 23.554 ms/op
                 getUser·p1.00:   24.084 ms/op

Iteration   2: 3.237 ±(99.9%) 0.010 ms/op
                 getUser·p0.00:   1.464 ms/op
                 getUser·p0.50:   3.097 ms/op
                 getUser·p0.90:   3.723 ms/op
                 getUser·p0.95:   4.243 ms/op
                 getUser·p0.99:   6.504 ms/op
                 getUser·p0.999:  12.386 ms/op
                 getUser·p0.9999: 28.582 ms/op
                 getUser·p1.00:   29.721 ms/op

Iteration   3: 3.266 ±(99.9%) 0.009 ms/op
                 getUser·p0.00:   1.561 ms/op
                 getUser·p0.50:   3.158 ms/op
                 getUser·p0.90:   3.744 ms/op
                 getUser·p0.95:   3.973 ms/op
                 getUser·p0.99:   5.480 ms/op
                 getUser·p0.999:  12.978 ms/op
                 getUser·p0.9999: 27.305 ms/op
                 getUser·p1.00:   28.869 ms/op



Result "org.apache.dubbo.benchmark.ClientPb.getUser":
  N = 295250
  mean =      3.248 ±(99.9%) 0.006 ms/op

  Histogram, ms/op:
    [ 0.000,  2.500) = 18092 
    [ 2.500,  5.000) = 269978 
    [ 5.000,  7.500) = 6134 
    [ 7.500, 10.000) = 586 
    [10.000, 12.500) = 129 
    [12.500, 15.000) = 10 
    [15.000, 17.500) = 1 
    [17.500, 20.000) = 48 
    [20.000, 22.500) = 81 
    [22.500, 25.000) = 72 
    [25.000, 27.500) = 85 

  Percentiles, ms/op:
      p(0.0000) =      1.233 ms/op
     p(50.0000) =      3.113 ms/op
     p(90.0000) =      3.731 ms/op
     p(95.0000) =      4.059 ms/op
     p(99.0000) =      6.185 ms/op
     p(99.9000) =     18.792 ms/op
     p(99.9900) =     27.689 ms/op
     p(99.9990) =     29.271 ms/op
     p(99.9999) =     29.721 ms/op
    p(100.0000) =     29.721 ms/op


# JMH version: 1.21
# VM version: JDK 1.8.0_362, OpenJDK 64-Bit Server VM, 25.362-b09
# VM invoker: /opt/hostedtoolcache/Java_Adopt_jdk/8.0.362-9/x64/jre/bin/java
# VM options: -Xmx1g -Xms1g -XX:MaxDirectMemorySize=1g -XX:+UseG1GC -Dserver.host=localhost -Dserver.port=8080 -Dbenchmark.output=dubbo-triple_output.md
# Warmup: 3 iterations, 10 s each
# Measurement: 3 iterations, 10 s each
# Timeout: 10 min per iteration
# Threads: 32 threads, will synchronize iterations
# Benchmark mode: Sampling time
# Benchmark: org.apache.dubbo.benchmark.ClientPb.listUser

# Run progress: 91.67% complete, ETA 00:01:05
# Fork: 1 of 1
# Warmup Iteration   1: 12.422 ±(99.9%) 0.151 ms/op
# Warmup Iteration   2: 4.300 ±(99.9%) 0.021 ms/op
# Warmup Iteration   3: 4.214 ±(99.9%) 0.014 ms/op
Iteration   1: 4.185 ±(99.9%) 0.013 ms/op
                 listUser·p0.00:   1.561 ms/op
                 listUser·p0.50:   3.969 ms/op
                 listUser·p0.90:   4.948 ms/op
                 listUser·p0.95:   5.480 ms/op
                 listUser·p0.99:   7.651 ms/op
                 listUser·p0.999:  22.741 ms/op
                 listUser·p0.9999: 25.407 ms/op
                 listUser·p1.00:   27.984 ms/op

Iteration   2: 4.071 ±(99.9%) 0.010 ms/op
                 listUser·p0.00:   2.376 ms/op
                 listUser·p0.50:   4.002 ms/op
                 listUser·p0.90:   4.350 ms/op
                 listUser·p0.95:   4.817 ms/op
                 listUser·p0.99:   7.094 ms/op
                 listUser·p0.999:  16.810 ms/op
                 listUser·p0.9999: 19.370 ms/op
                 listUser·p1.00:   20.185 ms/op

Iteration   3: 4.174 ±(99.9%) 0.012 ms/op
                 listUser·p0.00:   2.388 ms/op
                 listUser·p0.50:   3.985 ms/op
                 listUser·p0.90:   4.768 ms/op
                 listUser·p0.95:   5.136 ms/op
                 listUser·p0.99:   8.108 ms/op
                 listUser·p0.999:  17.302 ms/op
                 listUser·p0.9999: 19.988 ms/op
                 listUser·p1.00:   20.611 ms/op



Result "org.apache.dubbo.benchmark.ClientPb.listUser":
  N = 231807
  mean =      4.143 ±(99.9%) 0.007 ms/op

  Histogram, ms/op:
    [ 0.000,  2.500) = 23 
    [ 2.500,  5.000) = 216911 
    [ 5.000,  7.500) = 12381 
    [ 7.500, 10.000) = 1526 
    [10.000, 12.500) = 333 
    [12.500, 15.000) = 136 
    [15.000, 17.500) = 248 
    [17.500, 20.000) = 115 
    [20.000, 22.500) = 50 
    [22.500, 25.000) = 72 
    [25.000, 27.500) = 10 

  Percentiles, ms/op:
      p(0.0000) =      1.561 ms/op
     p(50.0000) =      3.990 ms/op
     p(90.0000) =      4.702 ms/op
     p(95.0000) =      5.186 ms/op
     p(99.0000) =      7.643 ms/op
     p(99.9000) =     17.695 ms/op
     p(99.9900) =     23.989 ms/op
     p(99.9990) =     27.582 ms/op
     p(99.9999) =     27.984 ms/op
    p(100.0000) =     27.984 ms/op


# Run complete. Total time: 00:13:10

REMEMBER: The numbers below are just data. To gain reusable insights, you need to follow up on
why the numbers are the way they are. Use profilers (see -prof, -lprof), design factorial
experiments, perform baseline and negative tests that provide experimental control, make sure
the benchmarking environment is safe on JVM/OS/HW level, ask for reviews from the domain experts.
Do not assume the numbers tell you what you want them to tell.

Benchmark                                 Mode     Cnt   Score   Error   Units
ClientPb.createUser                      thrpt       3  10.006 ± 3.084  ops/ms
ClientPb.existUser                       thrpt       3   9.550 ± 2.769  ops/ms
ClientPb.getUser                         thrpt       3   9.172 ± 4.610  ops/ms
ClientPb.listUser                        thrpt       3   8.289 ± 0.708  ops/ms
ClientPb.createUser                       avgt       3   3.379 ± 1.630   ms/op
ClientPb.existUser                        avgt       3   3.114 ± 1.302   ms/op
ClientPb.getUser                          avgt       3   3.343 ± 2.171   ms/op
ClientPb.listUser                         avgt       3   4.027 ± 2.129   ms/op
ClientPb.createUser                     sample  292977   3.275 ± 0.005   ms/op
ClientPb.createUser:createUser·p0.00    sample           1.159           ms/op
ClientPb.createUser:createUser·p0.50    sample           3.174           ms/op
ClientPb.createUser:createUser·p0.90    sample           3.670           ms/op
ClientPb.createUser:createUser·p0.95    sample           3.994           ms/op
ClientPb.createUser:createUser·p0.99    sample           5.882           ms/op
ClientPb.createUser:createUser·p0.999   sample          15.254           ms/op
ClientPb.createUser:createUser·p0.9999  sample          28.443           ms/op
ClientPb.createUser:createUser·p1.00    sample          31.425           ms/op
ClientPb.existUser                      sample  284733   3.369 ± 0.006   ms/op
ClientPb.existUser:existUser·p0.00      sample           1.311           ms/op
ClientPb.existUser:existUser·p0.50      sample           3.326           ms/op
ClientPb.existUser:existUser·p0.90      sample           3.756           ms/op
ClientPb.existUser:existUser·p0.95      sample           4.227           ms/op
ClientPb.existUser:existUser·p0.99      sample           5.890           ms/op
ClientPb.existUser:existUser·p0.999     sample          21.498           ms/op
ClientPb.existUser:existUser·p0.9999    sample          29.655           ms/op
ClientPb.existUser:existUser·p1.00      sample          30.999           ms/op
ClientPb.getUser                        sample  295250   3.248 ± 0.006   ms/op
ClientPb.getUser:getUser·p0.00          sample           1.233           ms/op
ClientPb.getUser:getUser·p0.50          sample           3.113           ms/op
ClientPb.getUser:getUser·p0.90          sample           3.731           ms/op
ClientPb.getUser:getUser·p0.95          sample           4.059           ms/op
ClientPb.getUser:getUser·p0.99          sample           6.185           ms/op
ClientPb.getUser:getUser·p0.999         sample          18.792           ms/op
ClientPb.getUser:getUser·p0.9999        sample          27.689           ms/op
ClientPb.getUser:getUser·p1.00          sample          29.721           ms/op
ClientPb.listUser                       sample  231807   4.143 ± 0.007   ms/op
ClientPb.listUser:listUser·p0.00        sample           1.561           ms/op
ClientPb.listUser:listUser·p0.50        sample           3.990           ms/op
ClientPb.listUser:listUser·p0.90        sample           4.702           ms/op
ClientPb.listUser:listUser·p0.95        sample           5.186           ms/op
ClientPb.listUser:listUser·p0.99        sample           7.643           ms/op
ClientPb.listUser:listUser·p0.999       sample          17.695           ms/op
ClientPb.listUser:listUser·p0.9999      sample          23.989           ms/op
ClientPb.listUser:listUser·p1.00        sample          27.984           ms/op
