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
# Warmup Iteration   1: 2.378 ops/ms
# Warmup Iteration   2: 5.810 ops/ms
# Warmup Iteration   3: 9.327 ops/ms
Iteration   1: 9.779 ops/ms
Iteration   2: 9.840 ops/ms
Iteration   3: 9.581 ops/ms


Result "org.apache.dubbo.benchmark.ClientPb.createUser":
  9.733 ±(99.9%) 2.465 ops/ms [Average]
  (min, avg, max) = (9.581, 9.733, 9.840), stdev = 0.135
  CI (99.9%): [7.268, 12.199] (assumes normal distribution)


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

# Run progress: 8.33% complete, ETA 00:12:07
# Fork: 1 of 1
# Warmup Iteration   1: 3.596 ops/ms
# Warmup Iteration   2: 9.325 ops/ms
# Warmup Iteration   3: 10.590 ops/ms
Iteration   1: 10.412 ops/ms
Iteration   2: 10.399 ops/ms
Iteration   3: 10.386 ops/ms


Result "org.apache.dubbo.benchmark.ClientPb.existUser":
  10.399 ±(99.9%) 0.241 ops/ms [Average]
  (min, avg, max) = (10.386, 10.399, 10.412), stdev = 0.013
  CI (99.9%): [10.158, 10.640] (assumes normal distribution)


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
# Warmup Iteration   1: 3.589 ops/ms
# Warmup Iteration   2: 8.537 ops/ms
# Warmup Iteration   3: 9.537 ops/ms
Iteration   1: 10.137 ops/ms
Iteration   2: 10.344 ops/ms
Iteration   3: 9.595 ops/ms


Result "org.apache.dubbo.benchmark.ClientPb.getUser":
  10.025 ±(99.9%) 7.049 ops/ms [Average]
  (min, avg, max) = (9.595, 10.025, 10.344), stdev = 0.386
  CI (99.9%): [2.976, 17.074] (assumes normal distribution)


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

# Run progress: 25.00% complete, ETA 00:09:51
# Fork: 1 of 1
# Warmup Iteration   1: 3.142 ops/ms
# Warmup Iteration   2: 7.878 ops/ms
# Warmup Iteration   3: 8.571 ops/ms
Iteration   1: 8.495 ops/ms
Iteration   2: 8.485 ops/ms
Iteration   3: 8.399 ops/ms


Result "org.apache.dubbo.benchmark.ClientPb.listUser":
  8.460 ±(99.9%) 0.960 ops/ms [Average]
  (min, avg, max) = (8.399, 8.460, 8.495), stdev = 0.053
  CI (99.9%): [7.500, 9.420] (assumes normal distribution)


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

# Run progress: 33.33% complete, ETA 00:08:46
# Fork: 1 of 1
# Warmup Iteration   1: 9.299 ±(99.9%) 0.044 ms/op
# Warmup Iteration   2: 3.566 ±(99.9%) 0.007 ms/op
# Warmup Iteration   3: 3.271 ±(99.9%) 0.003 ms/op
Iteration   1: 3.195 ±(99.9%) 0.007 ms/op
Iteration   2: 3.218 ±(99.9%) 0.008 ms/op
Iteration   3: 3.230 ±(99.9%) 0.009 ms/op


Result "org.apache.dubbo.benchmark.ClientPb.createUser":
  3.214 ±(99.9%) 0.328 ms/op [Average]
  (min, avg, max) = (3.195, 3.214, 3.230), stdev = 0.018
  CI (99.9%): [2.887, 3.542] (assumes normal distribution)


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

# Run progress: 41.67% complete, ETA 00:07:39
# Fork: 1 of 1
# Warmup Iteration   1: 7.331 ±(99.9%) 0.024 ms/op
# Warmup Iteration   2: 3.231 ±(99.9%) 0.002 ms/op
# Warmup Iteration   3: 3.163 ±(99.9%) 0.004 ms/op
Iteration   1: 3.061 ±(99.9%) 0.007 ms/op
Iteration   2: 3.068 ±(99.9%) 0.004 ms/op
Iteration   3: 3.002 ±(99.9%) 0.005 ms/op


Result "org.apache.dubbo.benchmark.ClientPb.existUser":
  3.044 ±(99.9%) 0.655 ms/op [Average]
  (min, avg, max) = (3.002, 3.044, 3.068), stdev = 0.036
  CI (99.9%): [2.389, 3.699] (assumes normal distribution)


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

# Run progress: 50.00% complete, ETA 00:06:34
# Fork: 1 of 1
# Warmup Iteration   1: 8.435 ±(99.9%) 0.027 ms/op
# Warmup Iteration   2: 3.492 ±(99.9%) 0.003 ms/op
# Warmup Iteration   3: 3.199 ±(99.9%) 0.002 ms/op
Iteration   1: 3.188 ±(99.9%) 0.003 ms/op
Iteration   2: 3.189 ±(99.9%) 0.005 ms/op
Iteration   3: 3.192 ±(99.9%) 0.004 ms/op


Result "org.apache.dubbo.benchmark.ClientPb.getUser":
  3.190 ±(99.9%) 0.038 ms/op [Average]
  (min, avg, max) = (3.188, 3.190, 3.192), stdev = 0.002
  CI (99.9%): [3.152, 3.228] (assumes normal distribution)


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

# Run progress: 58.33% complete, ETA 00:05:28
# Fork: 1 of 1
# Warmup Iteration   1: 9.328 ±(99.9%) 0.030 ms/op
# Warmup Iteration   2: 4.173 ±(99.9%) 0.007 ms/op
# Warmup Iteration   3: 3.810 ±(99.9%) 0.010 ms/op
Iteration   1: 3.778 ±(99.9%) 0.012 ms/op
Iteration   2: 3.862 ±(99.9%) 0.006 ms/op
Iteration   3: 3.715 ±(99.9%) 0.013 ms/op


Result "org.apache.dubbo.benchmark.ClientPb.listUser":
  3.785 ±(99.9%) 1.339 ms/op [Average]
  (min, avg, max) = (3.715, 3.785, 3.862), stdev = 0.073
  CI (99.9%): [2.446, 5.124] (assumes normal distribution)


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

# Run progress: 66.67% complete, ETA 00:04:22
# Fork: 1 of 1
# Warmup Iteration   1: 9.313 ±(99.9%) 0.119 ms/op
# Warmup Iteration   2: 4.088 ±(99.9%) 0.020 ms/op
# Warmup Iteration   3: 3.261 ±(99.9%) 0.009 ms/op
Iteration   1: 3.145 ±(99.9%) 0.008 ms/op
                 createUser·p0.00:   0.327 ms/op
                 createUser·p0.50:   3.152 ms/op
                 createUser·p0.90:   3.314 ms/op
                 createUser·p0.95:   3.424 ms/op
                 createUser·p0.99:   5.489 ms/op
                 createUser·p0.999:  10.411 ms/op
                 createUser·p0.9999: 27.772 ms/op
                 createUser·p1.00:   29.524 ms/op

Iteration   2: 3.167 ±(99.9%) 0.008 ms/op
                 createUser·p0.00:   1.612 ms/op
                 createUser·p0.50:   3.056 ms/op
                 createUser·p0.90:   3.531 ms/op
                 createUser·p0.95:   3.830 ms/op
                 createUser·p0.99:   5.259 ms/op
                 createUser·p0.999:  20.120 ms/op
                 createUser·p0.9999: 22.312 ms/op
                 createUser·p1.00:   22.610 ms/op

Iteration   3: 3.206 ±(99.9%) 0.007 ms/op
                 createUser·p0.00:   1.286 ms/op
                 createUser·p0.50:   3.174 ms/op
                 createUser·p0.90:   3.539 ms/op
                 createUser·p0.95:   3.813 ms/op
                 createUser·p0.99:   5.472 ms/op
                 createUser·p0.999:  14.877 ms/op
                 createUser·p0.9999: 19.431 ms/op
                 createUser·p1.00:   19.431 ms/op



Result "org.apache.dubbo.benchmark.ClientPb.createUser":
  N = 302456
  mean =      3.172 ±(99.9%) 0.005 ms/op

  Histogram, ms/op:
    [ 0.000,  2.500) = 19553 
    [ 2.500,  5.000) = 278319 
    [ 5.000,  7.500) = 3752 
    [ 7.500, 10.000) = 386 
    [10.000, 12.500) = 70 
    [12.500, 15.000) = 58 
    [15.000, 17.500) = 70 
    [17.500, 20.000) = 61 
    [20.000, 22.500) = 118 
    [22.500, 25.000) = 33 
    [25.000, 27.500) = 25 

  Percentiles, ms/op:
      p(0.0000) =      0.327 ms/op
     p(50.0000) =      3.133 ms/op
     p(90.0000) =      3.453 ms/op
     p(95.0000) =      3.736 ms/op
     p(99.0000) =      5.423 ms/op
     p(99.9000) =     15.278 ms/op
     p(99.9900) =     26.247 ms/op
     p(99.9990) =     29.442 ms/op
     p(99.9999) =     29.524 ms/op
    p(100.0000) =     29.524 ms/op


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

# Run progress: 75.00% complete, ETA 00:03:17
# Fork: 1 of 1
# Warmup Iteration   1: 7.022 ±(99.9%) 0.083 ms/op
# Warmup Iteration   2: 3.381 ±(99.9%) 0.011 ms/op
# Warmup Iteration   3: 3.063 ±(99.9%) 0.007 ms/op
Iteration   1: 3.071 ±(99.9%) 0.007 ms/op
                 existUser·p0.00:   1.432 ms/op
                 existUser·p0.50:   3.101 ms/op
                 existUser·p0.90:   3.207 ms/op
                 existUser·p0.95:   3.281 ms/op
                 existUser·p0.99:   5.210 ms/op
                 existUser·p0.999:  10.550 ms/op
                 existUser·p0.9999: 20.302 ms/op
                 existUser·p1.00:   20.677 ms/op

Iteration   2: 3.023 ±(99.9%) 0.007 ms/op
                 existUser·p0.00:   1.604 ms/op
                 existUser·p0.50:   2.953 ms/op
                 existUser·p0.90:   3.248 ms/op
                 existUser·p0.95:   3.432 ms/op
                 existUser·p0.99:   5.095 ms/op
                 existUser·p0.999:  8.901 ms/op
                 existUser·p0.9999: 21.674 ms/op
                 existUser·p1.00:   22.872 ms/op

Iteration   3: 3.170 ±(99.9%) 0.007 ms/op
                 existUser·p0.00:   1.386 ms/op
                 existUser·p0.50:   3.154 ms/op
                 existUser·p0.90:   3.494 ms/op
                 existUser·p0.95:   3.797 ms/op
                 existUser·p0.99:   5.439 ms/op
                 existUser·p0.999:  12.124 ms/op
                 existUser·p0.9999: 20.447 ms/op
                 existUser·p1.00:   20.775 ms/op



Result "org.apache.dubbo.benchmark.ClientPb.existUser":
  N = 310809
  mean =      3.087 ±(99.9%) 0.004 ms/op

  Histogram, ms/op:
    [ 0.000,  2.500) = 28138 
    [ 2.500,  5.000) = 278085 
    [ 5.000,  7.500) = 3914 
    [ 7.500, 10.000) = 344 
    [10.000, 12.500) = 40 
    [12.500, 15.000) = 11 
    [15.000, 17.500) = 51 
    [17.500, 20.000) = 108 
    [20.000, 22.500) = 117 
    [22.500, 25.000) = 1 
    [25.000, 27.500) = 0 

  Percentiles, ms/op:
      p(0.0000) =      1.386 ms/op
     p(50.0000) =      3.084 ms/op
     p(90.0000) =      3.301 ms/op
     p(95.0000) =      3.547 ms/op
     p(99.0000) =      5.210 ms/op
     p(99.9000) =     11.082 ms/op
     p(99.9900) =     21.332 ms/op
     p(99.9990) =     22.275 ms/op
     p(99.9999) =     22.872 ms/op
    p(100.0000) =     22.872 ms/op


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

# Run progress: 83.33% complete, ETA 00:02:11
# Fork: 1 of 1
# Warmup Iteration   1: 8.656 ±(99.9%) 0.100 ms/op
# Warmup Iteration   2: 3.479 ±(99.9%) 0.013 ms/op
# Warmup Iteration   3: 3.317 ±(99.9%) 0.010 ms/op
Iteration   1: 3.209 ±(99.9%) 0.008 ms/op
                 getUser·p0.00:   1.001 ms/op
                 getUser·p0.50:   3.142 ms/op
                 getUser·p0.90:   3.719 ms/op
                 getUser·p0.95:   3.908 ms/op
                 getUser·p0.99:   5.489 ms/op
                 getUser·p0.999:  16.941 ms/op
                 getUser·p0.9999: 18.912 ms/op
                 getUser·p1.00:   20.218 ms/op

Iteration   2: 3.180 ±(99.9%) 0.008 ms/op
                 getUser·p0.00:   1.470 ms/op
                 getUser·p0.50:   3.121 ms/op
                 getUser·p0.90:   3.547 ms/op
                 getUser·p0.95:   3.977 ms/op
                 getUser·p0.99:   5.554 ms/op
                 getUser·p0.999:  13.894 ms/op
                 getUser·p0.9999: 22.469 ms/op
                 getUser·p1.00:   23.101 ms/op

Iteration   3: 3.373 ±(99.9%) 0.009 ms/op
                 getUser·p0.00:   1.130 ms/op
                 getUser·p0.50:   3.252 ms/op
                 getUser·p0.90:   4.178 ms/op
                 getUser·p0.95:   4.448 ms/op
                 getUser·p0.99:   5.759 ms/op
                 getUser·p0.999:  17.060 ms/op
                 getUser·p0.9999: 21.447 ms/op
                 getUser·p1.00:   22.675 ms/op



Result "org.apache.dubbo.benchmark.ClientPb.getUser":
  N = 294926
  mean =      3.252 ±(99.9%) 0.005 ms/op

  Histogram, ms/op:
    [ 0.000,  2.500) = 21687 
    [ 2.500,  5.000) = 268140 
    [ 5.000,  7.500) = 3973 
    [ 7.500, 10.000) = 698 
    [10.000, 12.500) = 58 
    [12.500, 15.000) = 38 
    [15.000, 17.500) = 80 
    [17.500, 20.000) = 152 
    [20.000, 22.500) = 89 
    [22.500, 25.000) = 11 
    [25.000, 27.500) = 0 

  Percentiles, ms/op:
      p(0.0000) =      1.001 ms/op
     p(50.0000) =      3.166 ms/op
     p(90.0000) =      3.752 ms/op
     p(95.0000) =      4.243 ms/op
     p(99.0000) =      5.562 ms/op
     p(99.9000) =     16.908 ms/op
     p(99.9900) =     22.004 ms/op
     p(99.9990) =     22.938 ms/op
     p(99.9999) =     23.101 ms/op
    p(100.0000) =     23.101 ms/op


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

# Run progress: 91.67% complete, ETA 00:01:05
# Fork: 1 of 1
# Warmup Iteration   1: 8.978 ±(99.9%) 0.111 ms/op
# Warmup Iteration   2: 4.281 ±(99.9%) 0.019 ms/op
# Warmup Iteration   3: 3.777 ±(99.9%) 0.010 ms/op
Iteration   1: 3.697 ±(99.9%) 0.008 ms/op
                 listUser·p0.00:   2.232 ms/op
                 listUser·p0.50:   3.674 ms/op
                 listUser·p0.90:   3.789 ms/op
                 listUser·p0.95:   4.026 ms/op
                 listUser·p0.99:   6.644 ms/op
                 listUser·p0.999:  14.523 ms/op
                 listUser·p0.9999: 16.510 ms/op
                 listUser·p1.00:   16.908 ms/op

Iteration   2: 3.733 ±(99.9%) 0.009 ms/op
                 listUser·p0.00:   1.810 ms/op
                 listUser·p0.50:   3.654 ms/op
                 listUser·p0.90:   3.936 ms/op
                 listUser·p0.95:   4.276 ms/op
                 listUser·p0.99:   6.906 ms/op
                 listUser·p0.999:  15.671 ms/op
                 listUser·p0.9999: 17.400 ms/op
                 listUser·p1.00:   17.400 ms/op

Iteration   3: 3.630 ±(99.9%) 0.006 ms/op
                 listUser·p0.00:   2.191 ms/op
                 listUser·p0.50:   3.580 ms/op
                 listUser·p0.90:   3.736 ms/op
                 listUser·p0.95:   3.842 ms/op
                 listUser·p0.99:   5.652 ms/op
                 listUser·p0.999:  12.321 ms/op
                 listUser·p0.9999: 14.385 ms/op
                 listUser·p1.00:   14.680 ms/op



Result "org.apache.dubbo.benchmark.ClientPb.listUser":
  N = 260512
  mean =      3.686 ±(99.9%) 0.004 ms/op

  Histogram, ms/op:
    [ 0.000,  1.250) = 0 
    [ 1.250,  2.500) = 67 
    [ 2.500,  3.750) = 219294 
    [ 3.750,  5.000) = 35704 
    [ 5.000,  6.250) = 2216 
    [ 6.250,  7.500) = 1659 
    [ 7.500,  8.750) = 667 
    [ 8.750, 10.000) = 282 
    [10.000, 11.250) = 122 
    [11.250, 12.500) = 117 
    [12.500, 13.750) = 140 
    [13.750, 15.000) = 75 
    [15.000, 16.250) = 90 
    [16.250, 17.500) = 79 
    [17.500, 18.750) = 0 

  Percentiles, ms/op:
      p(0.0000) =      1.810 ms/op
     p(50.0000) =      3.637 ms/op
     p(90.0000) =      3.801 ms/op
     p(95.0000) =      4.088 ms/op
     p(99.0000) =      6.554 ms/op
     p(99.9000) =     13.566 ms/op
     p(99.9900) =     16.974 ms/op
     p(99.9990) =     17.400 ms/op
     p(99.9999) =     17.400 ms/op
    p(100.0000) =     17.400 ms/op


# Run complete. Total time: 00:13:11

REMEMBER: The numbers below are just data. To gain reusable insights, you need to follow up on
why the numbers are the way they are. Use profilers (see -prof, -lprof), design factorial
experiments, perform baseline and negative tests that provide experimental control, make sure
the benchmarking environment is safe on JVM/OS/HW level, ask for reviews from the domain experts.
Do not assume the numbers tell you what you want them to tell.

Benchmark                                 Mode     Cnt   Score   Error   Units
ClientPb.createUser                      thrpt       3   9.733 ± 2.465  ops/ms
ClientPb.existUser                       thrpt       3  10.399 ± 0.241  ops/ms
ClientPb.getUser                         thrpt       3  10.025 ± 7.049  ops/ms
ClientPb.listUser                        thrpt       3   8.460 ± 0.960  ops/ms
ClientPb.createUser                       avgt       3   3.214 ± 0.328   ms/op
ClientPb.existUser                        avgt       3   3.044 ± 0.655   ms/op
ClientPb.getUser                          avgt       3   3.190 ± 0.038   ms/op
ClientPb.listUser                         avgt       3   3.785 ± 1.339   ms/op
ClientPb.createUser                     sample  302456   3.172 ± 0.005   ms/op
ClientPb.createUser:createUser·p0.00    sample           0.327           ms/op
ClientPb.createUser:createUser·p0.50    sample           3.133           ms/op
ClientPb.createUser:createUser·p0.90    sample           3.453           ms/op
ClientPb.createUser:createUser·p0.95    sample           3.736           ms/op
ClientPb.createUser:createUser·p0.99    sample           5.423           ms/op
ClientPb.createUser:createUser·p0.999   sample          15.278           ms/op
ClientPb.createUser:createUser·p0.9999  sample          26.247           ms/op
ClientPb.createUser:createUser·p1.00    sample          29.524           ms/op
ClientPb.existUser                      sample  310809   3.087 ± 0.004   ms/op
ClientPb.existUser:existUser·p0.00      sample           1.386           ms/op
ClientPb.existUser:existUser·p0.50      sample           3.084           ms/op
ClientPb.existUser:existUser·p0.90      sample           3.301           ms/op
ClientPb.existUser:existUser·p0.95      sample           3.547           ms/op
ClientPb.existUser:existUser·p0.99      sample           5.210           ms/op
ClientPb.existUser:existUser·p0.999     sample          11.082           ms/op
ClientPb.existUser:existUser·p0.9999    sample          21.332           ms/op
ClientPb.existUser:existUser·p1.00      sample          22.872           ms/op
ClientPb.getUser                        sample  294926   3.252 ± 0.005   ms/op
ClientPb.getUser:getUser·p0.00          sample           1.001           ms/op
ClientPb.getUser:getUser·p0.50          sample           3.166           ms/op
ClientPb.getUser:getUser·p0.90          sample           3.752           ms/op
ClientPb.getUser:getUser·p0.95          sample           4.243           ms/op
ClientPb.getUser:getUser·p0.99          sample           5.562           ms/op
ClientPb.getUser:getUser·p0.999         sample          16.908           ms/op
ClientPb.getUser:getUser·p0.9999        sample          22.004           ms/op
ClientPb.getUser:getUser·p1.00          sample          23.101           ms/op
ClientPb.listUser                       sample  260512   3.686 ± 0.004   ms/op
ClientPb.listUser:listUser·p0.00        sample           1.810           ms/op
ClientPb.listUser:listUser·p0.50        sample           3.637           ms/op
ClientPb.listUser:listUser·p0.90        sample           3.801           ms/op
ClientPb.listUser:listUser·p0.95        sample           4.088           ms/op
ClientPb.listUser:listUser·p0.99        sample           6.554           ms/op
ClientPb.listUser:listUser·p0.999       sample          13.566           ms/op
ClientPb.listUser:listUser·p0.9999      sample          16.974           ms/op
ClientPb.listUser:listUser·p1.00        sample          17.400           ms/op
