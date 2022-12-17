# JMH version: 1.21
# VM version: JDK 1.8.0_352, OpenJDK 64-Bit Server VM, 25.352-b08
# VM invoker: /opt/hostedtoolcache/Java_Adopt_jdk/8.0.352-8/x64/jre/bin/java
# VM options: -Xmx1g -Xms1g -XX:MaxDirectMemorySize=1g -XX:+UseG1GC -Dserver.host=localhost -Dserver.port=8080 -Dbenchmark.output=dubbo-triple_output.md
# Warmup: 3 iterations, 10 s each
# Measurement: 3 iterations, 10 s each
# Timeout: 10 min per iteration
# Threads: 32 threads, will synchronize iterations
# Benchmark mode: Throughput, ops/time
# Benchmark: org.apache.dubbo.benchmark.ClientPb.createUser

# Run progress: 0.00% complete, ETA 00:12:00
# Fork: 1 of 1
# Warmup Iteration   1: 2.230 ops/ms
# Warmup Iteration   2: 5.920 ops/ms
# Warmup Iteration   3: 8.408 ops/ms
Iteration   1: 9.434 ops/ms
Iteration   2: 8.914 ops/ms
Iteration   3: 9.007 ops/ms


Result "org.apache.dubbo.benchmark.ClientPb.createUser":
  9.118 ±(99.9%) 5.059 ops/ms [Average]
  (min, avg, max) = (8.914, 9.118, 9.434), stdev = 0.277
  CI (99.9%): [4.059, 14.177] (assumes normal distribution)


# JMH version: 1.21
# VM version: JDK 1.8.0_352, OpenJDK 64-Bit Server VM, 25.352-b08
# VM invoker: /opt/hostedtoolcache/Java_Adopt_jdk/8.0.352-8/x64/jre/bin/java
# VM options: -Xmx1g -Xms1g -XX:MaxDirectMemorySize=1g -XX:+UseG1GC -Dserver.host=localhost -Dserver.port=8080 -Dbenchmark.output=dubbo-triple_output.md
# Warmup: 3 iterations, 10 s each
# Measurement: 3 iterations, 10 s each
# Timeout: 10 min per iteration
# Threads: 32 threads, will synchronize iterations
# Benchmark mode: Throughput, ops/time
# Benchmark: org.apache.dubbo.benchmark.ClientPb.existUser

# Run progress: 8.33% complete, ETA 00:12:08
# Fork: 1 of 1
# Warmup Iteration   1: 2.935 ops/ms
# Warmup Iteration   2: 8.988 ops/ms
# Warmup Iteration   3: 9.539 ops/ms
Iteration   1: 10.042 ops/ms
Iteration   2: 9.855 ops/ms
Iteration   3: 9.696 ops/ms


Result "org.apache.dubbo.benchmark.ClientPb.existUser":
  9.864 ±(99.9%) 3.164 ops/ms [Average]
  (min, avg, max) = (9.696, 9.864, 10.042), stdev = 0.173
  CI (99.9%): [6.700, 13.029] (assumes normal distribution)


# JMH version: 1.21
# VM version: JDK 1.8.0_352, OpenJDK 64-Bit Server VM, 25.352-b08
# VM invoker: /opt/hostedtoolcache/Java_Adopt_jdk/8.0.352-8/x64/jre/bin/java
# VM options: -Xmx1g -Xms1g -XX:MaxDirectMemorySize=1g -XX:+UseG1GC -Dserver.host=localhost -Dserver.port=8080 -Dbenchmark.output=dubbo-triple_output.md
# Warmup: 3 iterations, 10 s each
# Measurement: 3 iterations, 10 s each
# Timeout: 10 min per iteration
# Threads: 32 threads, will synchronize iterations
# Benchmark mode: Throughput, ops/time
# Benchmark: org.apache.dubbo.benchmark.ClientPb.getUser

# Run progress: 16.67% complete, ETA 00:11:01
# Fork: 1 of 1
# Warmup Iteration   1: 3.041 ops/ms
# Warmup Iteration   2: 8.906 ops/ms
# Warmup Iteration   3: 8.902 ops/ms
Iteration   1: 9.592 ops/ms
Iteration   2: 9.229 ops/ms
Iteration   3: 9.369 ops/ms


Result "org.apache.dubbo.benchmark.ClientPb.getUser":
  9.397 ±(99.9%) 3.342 ops/ms [Average]
  (min, avg, max) = (9.229, 9.397, 9.592), stdev = 0.183
  CI (99.9%): [6.055, 12.738] (assumes normal distribution)


# JMH version: 1.21
# VM version: JDK 1.8.0_352, OpenJDK 64-Bit Server VM, 25.352-b08
# VM invoker: /opt/hostedtoolcache/Java_Adopt_jdk/8.0.352-8/x64/jre/bin/java
# VM options: -Xmx1g -Xms1g -XX:MaxDirectMemorySize=1g -XX:+UseG1GC -Dserver.host=localhost -Dserver.port=8080 -Dbenchmark.output=dubbo-triple_output.md
# Warmup: 3 iterations, 10 s each
# Measurement: 3 iterations, 10 s each
# Timeout: 10 min per iteration
# Threads: 32 threads, will synchronize iterations
# Benchmark mode: Throughput, ops/time
# Benchmark: org.apache.dubbo.benchmark.ClientPb.listUser

# Run progress: 25.00% complete, ETA 00:09:51
# Fork: 1 of 1
# Warmup Iteration   1: 2.811 ops/ms
# Warmup Iteration   2: 7.299 ops/ms
# Warmup Iteration   3: 7.718 ops/ms
Iteration   1: 7.575 ops/ms
Iteration   2: 8.079 ops/ms
Iteration   3: 7.894 ops/ms


Result "org.apache.dubbo.benchmark.ClientPb.listUser":
  7.849 ±(99.9%) 4.646 ops/ms [Average]
  (min, avg, max) = (7.575, 7.849, 8.079), stdev = 0.255
  CI (99.9%): [3.204, 12.495] (assumes normal distribution)


# JMH version: 1.21
# VM version: JDK 1.8.0_352, OpenJDK 64-Bit Server VM, 25.352-b08
# VM invoker: /opt/hostedtoolcache/Java_Adopt_jdk/8.0.352-8/x64/jre/bin/java
# VM options: -Xmx1g -Xms1g -XX:MaxDirectMemorySize=1g -XX:+UseG1GC -Dserver.host=localhost -Dserver.port=8080 -Dbenchmark.output=dubbo-triple_output.md
# Warmup: 3 iterations, 10 s each
# Measurement: 3 iterations, 10 s each
# Timeout: 10 min per iteration
# Threads: 32 threads, will synchronize iterations
# Benchmark mode: Average time, time/op
# Benchmark: org.apache.dubbo.benchmark.ClientPb.createUser

# Run progress: 33.33% complete, ETA 00:08:44
# Fork: 1 of 1
# Warmup Iteration   1: 10.829 ±(99.9%) 0.034 ms/op
# Warmup Iteration   2: 4.055 ±(99.9%) 0.004 ms/op
# Warmup Iteration   3: 3.647 ±(99.9%) 0.012 ms/op
Iteration   1: 3.588 ±(99.9%) 0.005 ms/op
Iteration   2: 3.425 ±(99.9%) 0.011 ms/op
Iteration   3: 3.311 ±(99.9%) 0.014 ms/op


Result "org.apache.dubbo.benchmark.ClientPb.createUser":
  3.441 ±(99.9%) 2.542 ms/op [Average]
  (min, avg, max) = (3.311, 3.441, 3.588), stdev = 0.139
  CI (99.9%): [0.899, 5.983] (assumes normal distribution)


# JMH version: 1.21
# VM version: JDK 1.8.0_352, OpenJDK 64-Bit Server VM, 25.352-b08
# VM invoker: /opt/hostedtoolcache/Java_Adopt_jdk/8.0.352-8/x64/jre/bin/java
# VM options: -Xmx1g -Xms1g -XX:MaxDirectMemorySize=1g -XX:+UseG1GC -Dserver.host=localhost -Dserver.port=8080 -Dbenchmark.output=dubbo-triple_output.md
# Warmup: 3 iterations, 10 s each
# Measurement: 3 iterations, 10 s each
# Timeout: 10 min per iteration
# Threads: 32 threads, will synchronize iterations
# Benchmark mode: Average time, time/op
# Benchmark: org.apache.dubbo.benchmark.ClientPb.existUser

# Run progress: 41.67% complete, ETA 00:07:40
# Fork: 1 of 1
# Warmup Iteration   1: 9.084 ±(99.9%) 0.032 ms/op
# Warmup Iteration   2: 3.588 ±(99.9%) 0.004 ms/op
# Warmup Iteration   3: 3.317 ±(99.9%) 0.009 ms/op
Iteration   1: 3.268 ±(99.9%) 0.009 ms/op
Iteration   2: 3.235 ±(99.9%) 0.009 ms/op
Iteration   3: 3.411 ±(99.9%) 0.007 ms/op


Result "org.apache.dubbo.benchmark.ClientPb.existUser":
  3.305 ±(99.9%) 1.702 ms/op [Average]
  (min, avg, max) = (3.235, 3.305, 3.411), stdev = 0.093
  CI (99.9%): [1.603, 5.007] (assumes normal distribution)


# JMH version: 1.21
# VM version: JDK 1.8.0_352, OpenJDK 64-Bit Server VM, 25.352-b08
# VM invoker: /opt/hostedtoolcache/Java_Adopt_jdk/8.0.352-8/x64/jre/bin/java
# VM options: -Xmx1g -Xms1g -XX:MaxDirectMemorySize=1g -XX:+UseG1GC -Dserver.host=localhost -Dserver.port=8080 -Dbenchmark.output=dubbo-triple_output.md
# Warmup: 3 iterations, 10 s each
# Measurement: 3 iterations, 10 s each
# Timeout: 10 min per iteration
# Threads: 32 threads, will synchronize iterations
# Benchmark mode: Average time, time/op
# Benchmark: org.apache.dubbo.benchmark.ClientPb.getUser

# Run progress: 50.00% complete, ETA 00:06:34
# Fork: 1 of 1
# Warmup Iteration   1: 8.717 ±(99.9%) 0.026 ms/op
# Warmup Iteration   2: 3.737 ±(99.9%) 0.006 ms/op
# Warmup Iteration   3: 3.487 ±(99.9%) 0.003 ms/op
Iteration   1: 3.313 ±(99.9%) 0.006 ms/op
Iteration   2: 3.416 ±(99.9%) 0.009 ms/op
Iteration   3: 3.323 ±(99.9%) 0.011 ms/op


Result "org.apache.dubbo.benchmark.ClientPb.getUser":
  3.351 ±(99.9%) 1.032 ms/op [Average]
  (min, avg, max) = (3.313, 3.351, 3.416), stdev = 0.057
  CI (99.9%): [2.318, 4.383] (assumes normal distribution)


# JMH version: 1.21
# VM version: JDK 1.8.0_352, OpenJDK 64-Bit Server VM, 25.352-b08
# VM invoker: /opt/hostedtoolcache/Java_Adopt_jdk/8.0.352-8/x64/jre/bin/java
# VM options: -Xmx1g -Xms1g -XX:MaxDirectMemorySize=1g -XX:+UseG1GC -Dserver.host=localhost -Dserver.port=8080 -Dbenchmark.output=dubbo-triple_output.md
# Warmup: 3 iterations, 10 s each
# Measurement: 3 iterations, 10 s each
# Timeout: 10 min per iteration
# Threads: 32 threads, will synchronize iterations
# Benchmark mode: Average time, time/op
# Benchmark: org.apache.dubbo.benchmark.ClientPb.listUser

# Run progress: 58.33% complete, ETA 00:05:28
# Fork: 1 of 1
# Warmup Iteration   1: 11.605 ±(99.9%) 0.033 ms/op
# Warmup Iteration   2: 4.611 ±(99.9%) 0.009 ms/op
# Warmup Iteration   3: 4.109 ±(99.9%) 0.009 ms/op
Iteration   1: 4.337 ±(99.9%) 0.010 ms/op
Iteration   2: 3.988 ±(99.9%) 0.011 ms/op
Iteration   3: 4.053 ±(99.9%) 0.012 ms/op


Result "org.apache.dubbo.benchmark.ClientPb.listUser":
  4.126 ±(99.9%) 3.382 ms/op [Average]
  (min, avg, max) = (3.988, 4.126, 4.337), stdev = 0.185
  CI (99.9%): [0.744, 7.508] (assumes normal distribution)


# JMH version: 1.21
# VM version: JDK 1.8.0_352, OpenJDK 64-Bit Server VM, 25.352-b08
# VM invoker: /opt/hostedtoolcache/Java_Adopt_jdk/8.0.352-8/x64/jre/bin/java
# VM options: -Xmx1g -Xms1g -XX:MaxDirectMemorySize=1g -XX:+UseG1GC -Dserver.host=localhost -Dserver.port=8080 -Dbenchmark.output=dubbo-triple_output.md
# Warmup: 3 iterations, 10 s each
# Measurement: 3 iterations, 10 s each
# Timeout: 10 min per iteration
# Threads: 32 threads, will synchronize iterations
# Benchmark mode: Sampling time
# Benchmark: org.apache.dubbo.benchmark.ClientPb.createUser

# Run progress: 66.67% complete, ETA 00:04:23
# Fork: 1 of 1
# Warmup Iteration   1: 9.802 ±(99.9%) 0.126 ms/op
# Warmup Iteration   2: 4.133 ±(99.9%) 0.019 ms/op
# Warmup Iteration   3: 3.610 ±(99.9%) 0.013 ms/op
Iteration   1: 3.406 ±(99.9%) 0.011 ms/op
                 createUser·p0.00:   1.589 ms/op
                 createUser·p0.50:   3.305 ms/op
                 createUser·p0.90:   3.944 ms/op
                 createUser·p0.95:   4.276 ms/op
                 createUser·p0.99:   6.000 ms/op
                 createUser·p0.999:  21.276 ms/op
                 createUser·p0.9999: 30.734 ms/op
                 createUser·p1.00:   32.702 ms/op

Iteration   2: 3.403 ±(99.9%) 0.011 ms/op
                 createUser·p0.00:   1.007 ms/op
                 createUser·p0.50:   3.260 ms/op
                 createUser·p0.90:   3.928 ms/op
                 createUser·p0.95:   4.588 ms/op
                 createUser·p0.99:   6.496 ms/op
                 createUser·p0.999:  23.168 ms/op
                 createUser·p0.9999: 28.541 ms/op
                 createUser·p1.00:   29.065 ms/op

Iteration   3: 3.481 ±(99.9%) 0.010 ms/op
                 createUser·p0.00:   1.399 ms/op
                 createUser·p0.50:   3.404 ms/op
                 createUser·p0.90:   3.994 ms/op
                 createUser·p0.95:   4.350 ms/op
                 createUser·p0.99:   5.972 ms/op
                 createUser·p0.999:  22.184 ms/op
                 createUser·p0.9999: 28.369 ms/op
                 createUser·p1.00:   29.164 ms/op



Result "org.apache.dubbo.benchmark.ClientPb.createUser":
  N = 279607
  mean =      3.430 ±(99.9%) 0.006 ms/op

  Histogram, ms/op:
    [ 0.000,  2.500) = 6291 
    [ 2.500,  5.000) = 265896 
    [ 5.000,  7.500) = 6206 
    [ 7.500, 10.000) = 660 
    [10.000, 12.500) = 205 
    [12.500, 15.000) = 37 
    [15.000, 17.500) = 24 
    [17.500, 20.000) = 0 
    [20.000, 22.500) = 28 
    [22.500, 25.000) = 124 
    [25.000, 27.500) = 65 
    [27.500, 30.000) = 51 
    [30.000, 32.500) = 19 
    [32.500, 35.000) = 1 
    [35.000, 37.500) = 0 

  Percentiles, ms/op:
      p(0.0000) =      1.007 ms/op
     p(50.0000) =      3.326 ms/op
     p(90.0000) =      3.957 ms/op
     p(95.0000) =      4.358 ms/op
     p(99.0000) =      6.201 ms/op
     p(99.9000) =     21.430 ms/op
     p(99.9900) =     29.264 ms/op
     p(99.9990) =     31.537 ms/op
     p(99.9999) =     32.702 ms/op
    p(100.0000) =     32.702 ms/op


# JMH version: 1.21
# VM version: JDK 1.8.0_352, OpenJDK 64-Bit Server VM, 25.352-b08
# VM invoker: /opt/hostedtoolcache/Java_Adopt_jdk/8.0.352-8/x64/jre/bin/java
# VM options: -Xmx1g -Xms1g -XX:MaxDirectMemorySize=1g -XX:+UseG1GC -Dserver.host=localhost -Dserver.port=8080 -Dbenchmark.output=dubbo-triple_output.md
# Warmup: 3 iterations, 10 s each
# Measurement: 3 iterations, 10 s each
# Timeout: 10 min per iteration
# Threads: 32 threads, will synchronize iterations
# Benchmark mode: Sampling time
# Benchmark: org.apache.dubbo.benchmark.ClientPb.existUser

# Run progress: 75.00% complete, ETA 00:03:17
# Fork: 1 of 1
# Warmup Iteration   1: 9.857 ±(99.9%) 0.125 ms/op
# Warmup Iteration   2: 3.692 ±(99.9%) 0.013 ms/op
# Warmup Iteration   3: 3.320 ±(99.9%) 0.009 ms/op
Iteration   1: 3.351 ±(99.9%) 0.010 ms/op
                 existUser·p0.00:   1.473 ms/op
                 existUser·p0.50:   3.269 ms/op
                 existUser·p0.90:   3.813 ms/op
                 existUser·p0.95:   4.448 ms/op
                 existUser·p0.99:   6.586 ms/op
                 existUser·p0.999:  18.607 ms/op
                 existUser·p0.9999: 27.841 ms/op
                 existUser·p1.00:   30.540 ms/op

Iteration   2: 3.375 ±(99.9%) 0.011 ms/op
                 existUser·p0.00:   1.151 ms/op
                 existUser·p0.50:   3.236 ms/op
                 existUser·p0.90:   4.030 ms/op
                 existUser·p0.95:   4.588 ms/op
                 existUser·p0.99:   5.988 ms/op
                 existUser·p0.999:  22.822 ms/op
                 existUser·p0.9999: 26.102 ms/op
                 existUser·p1.00:   26.739 ms/op

Iteration   3: 3.412 ±(99.9%) 0.011 ms/op
                 existUser·p0.00:   1.188 ms/op
                 existUser·p0.50:   3.273 ms/op
                 existUser·p0.90:   4.112 ms/op
                 existUser·p0.95:   4.669 ms/op
                 existUser·p0.99:   6.586 ms/op
                 existUser·p0.999:  21.571 ms/op
                 existUser·p0.9999: 29.357 ms/op
                 existUser·p1.00:   29.983 ms/op



Result "org.apache.dubbo.benchmark.ClientPb.existUser":
  N = 284192
  mean =      3.379 ±(99.9%) 0.006 ms/op

  Histogram, ms/op:
    [ 0.000,  2.500) = 11263 
    [ 2.500,  5.000) = 263468 
    [ 5.000,  7.500) = 8253 
    [ 7.500, 10.000) = 769 
    [10.000, 12.500) = 93 
    [12.500, 15.000) = 53 
    [15.000, 17.500) = 5 
    [17.500, 20.000) = 16 
    [20.000, 22.500) = 39 
    [22.500, 25.000) = 87 
    [25.000, 27.500) = 100 
    [27.500, 30.000) = 38 
    [30.000, 32.500) = 8 
    [32.500, 35.000) = 0 
    [35.000, 37.500) = 0 

  Percentiles, ms/op:
      p(0.0000) =      1.151 ms/op
     p(50.0000) =      3.256 ms/op
     p(90.0000) =      3.985 ms/op
     p(95.0000) =      4.596 ms/op
     p(99.0000) =      6.447 ms/op
     p(99.9000) =     18.770 ms/op
     p(99.9900) =     28.417 ms/op
     p(99.9990) =     30.474 ms/op
     p(99.9999) =     30.540 ms/op
    p(100.0000) =     30.540 ms/op


# JMH version: 1.21
# VM version: JDK 1.8.0_352, OpenJDK 64-Bit Server VM, 25.352-b08
# VM invoker: /opt/hostedtoolcache/Java_Adopt_jdk/8.0.352-8/x64/jre/bin/java
# VM options: -Xmx1g -Xms1g -XX:MaxDirectMemorySize=1g -XX:+UseG1GC -Dserver.host=localhost -Dserver.port=8080 -Dbenchmark.output=dubbo-triple_output.md
# Warmup: 3 iterations, 10 s each
# Measurement: 3 iterations, 10 s each
# Timeout: 10 min per iteration
# Threads: 32 threads, will synchronize iterations
# Benchmark mode: Sampling time
# Benchmark: org.apache.dubbo.benchmark.ClientPb.getUser

# Run progress: 83.33% complete, ETA 00:02:11
# Fork: 1 of 1
# Warmup Iteration   1: 9.703 ±(99.9%) 0.117 ms/op
# Warmup Iteration   2: 3.753 ±(99.9%) 0.014 ms/op
# Warmup Iteration   3: 3.609 ±(99.9%) 0.013 ms/op
Iteration   1: 3.552 ±(99.9%) 0.010 ms/op
                 getUser·p0.00:   1.372 ms/op
                 getUser·p0.50:   3.465 ms/op
                 getUser·p0.90:   4.121 ms/op
                 getUser·p0.95:   4.563 ms/op
                 getUser·p0.99:   6.365 ms/op
                 getUser·p0.999:  19.892 ms/op
                 getUser·p0.9999: 25.295 ms/op
                 getUser·p1.00:   26.149 ms/op

Iteration   2: 3.595 ±(99.9%) 0.010 ms/op
                 getUser·p0.00:   1.346 ms/op
                 getUser·p0.50:   3.490 ms/op
                 getUser·p0.90:   4.366 ms/op
                 getUser·p0.95:   4.825 ms/op
                 getUser·p0.99:   6.144 ms/op
                 getUser·p0.999:  12.713 ms/op
                 getUser·p0.9999: 25.449 ms/op
                 getUser·p1.00:   26.313 ms/op

Iteration   3: 3.522 ±(99.9%) 0.010 ms/op
                 getUser·p0.00:   1.489 ms/op
                 getUser·p0.50:   3.400 ms/op
                 getUser·p0.90:   3.990 ms/op
                 getUser·p0.95:   4.407 ms/op
                 getUser·p0.99:   6.587 ms/op
                 getUser·p0.999:  19.726 ms/op
                 getUser·p0.9999: 26.706 ms/op
                 getUser·p1.00:   27.984 ms/op



Result "org.apache.dubbo.benchmark.ClientPb.getUser":
  N = 270284
  mean =      3.556 ±(99.9%) 0.006 ms/op

  Histogram, ms/op:
    [ 0.000,  2.500) = 5216 
    [ 2.500,  5.000) = 255083 
    [ 5.000,  7.500) = 8802 
    [ 7.500, 10.000) = 763 
    [10.000, 12.500) = 129 
    [12.500, 15.000) = 32 
    [15.000, 17.500) = 0 
    [17.500, 20.000) = 25 
    [20.000, 22.500) = 91 
    [22.500, 25.000) = 68 
    [25.000, 27.500) = 73 

  Percentiles, ms/op:
      p(0.0000) =      1.346 ms/op
     p(50.0000) =      3.449 ms/op
     p(90.0000) =      4.157 ms/op
     p(95.0000) =      4.678 ms/op
     p(99.0000) =      6.398 ms/op
     p(99.9000) =     13.021 ms/op
     p(99.9900) =     26.278 ms/op
     p(99.9990) =     27.596 ms/op
     p(99.9999) =     27.984 ms/op
    p(100.0000) =     27.984 ms/op


# JMH version: 1.21
# VM version: JDK 1.8.0_352, OpenJDK 64-Bit Server VM, 25.352-b08
# VM invoker: /opt/hostedtoolcache/Java_Adopt_jdk/8.0.352-8/x64/jre/bin/java
# VM options: -Xmx1g -Xms1g -XX:MaxDirectMemorySize=1g -XX:+UseG1GC -Dserver.host=localhost -Dserver.port=8080 -Dbenchmark.output=dubbo-triple_output.md
# Warmup: 3 iterations, 10 s each
# Measurement: 3 iterations, 10 s each
# Timeout: 10 min per iteration
# Threads: 32 threads, will synchronize iterations
# Benchmark mode: Sampling time
# Benchmark: org.apache.dubbo.benchmark.ClientPb.listUser

# Run progress: 91.67% complete, ETA 00:01:05
# Fork: 1 of 1
# Warmup Iteration   1: 10.428 ±(99.9%) 0.137 ms/op
# Warmup Iteration   2: 4.474 ±(99.9%) 0.018 ms/op
# Warmup Iteration   3: 4.176 ±(99.9%) 0.014 ms/op
Iteration   1: 3.959 ±(99.9%) 0.012 ms/op
                 listUser·p0.00:   1.946 ms/op
                 listUser·p0.50:   3.838 ms/op
                 listUser·p0.90:   4.456 ms/op
                 listUser·p0.95:   4.809 ms/op
                 listUser·p0.99:   7.195 ms/op
                 listUser·p0.999:  21.468 ms/op
                 listUser·p0.9999: 23.875 ms/op
                 listUser·p1.00:   25.068 ms/op

Iteration   2: 4.144 ±(99.9%) 0.011 ms/op
                 listUser·p0.00:   2.134 ms/op
                 listUser·p0.50:   4.006 ms/op
                 listUser·p0.90:   4.735 ms/op
                 listUser·p0.95:   5.194 ms/op
                 listUser·p0.99:   8.046 ms/op
                 listUser·p0.999:  15.152 ms/op
                 listUser·p0.9999: 20.424 ms/op
                 listUser·p1.00:   21.332 ms/op

Iteration   3: 4.195 ±(99.9%) 0.011 ms/op
                 listUser·p0.00:   1.935 ms/op
                 listUser·p0.50:   4.104 ms/op
                 listUser·p0.90:   4.637 ms/op
                 listUser·p0.95:   4.866 ms/op
                 listUser·p0.99:   7.149 ms/op
                 listUser·p0.999:  17.531 ms/op
                 listUser·p0.9999: 31.752 ms/op
                 listUser·p1.00:   32.309 ms/op



Result "org.apache.dubbo.benchmark.ClientPb.listUser":
  N = 234178
  mean =      4.097 ±(99.9%) 0.007 ms/op

  Histogram, ms/op:
    [ 0.000,  2.500) = 66 
    [ 2.500,  5.000) = 223487 
    [ 5.000,  7.500) = 8103 
    [ 7.500, 10.000) = 1691 
    [10.000, 12.500) = 333 
    [12.500, 15.000) = 121 
    [15.000, 17.500) = 118 
    [17.500, 20.000) = 96 
    [20.000, 22.500) = 92 
    [22.500, 25.000) = 38 
    [25.000, 27.500) = 6 
    [27.500, 30.000) = 13 
    [30.000, 32.500) = 14 
    [32.500, 35.000) = 0 
    [35.000, 37.500) = 0 

  Percentiles, ms/op:
      p(0.0000) =      1.935 ms/op
     p(50.0000) =      3.985 ms/op
     p(90.0000) =      4.620 ms/op
     p(95.0000) =      4.940 ms/op
     p(99.0000) =      7.610 ms/op
     p(99.9000) =     17.760 ms/op
     p(99.9900) =     28.298 ms/op
     p(99.9990) =     32.045 ms/op
     p(99.9999) =     32.309 ms/op
    p(100.0000) =     32.309 ms/op


# Run complete. Total time: 00:13:11

REMEMBER: The numbers below are just data. To gain reusable insights, you need to follow up on
why the numbers are the way they are. Use profilers (see -prof, -lprof), design factorial
experiments, perform baseline and negative tests that provide experimental control, make sure
the benchmarking environment is safe on JVM/OS/HW level, ask for reviews from the domain experts.
Do not assume the numbers tell you what you want them to tell.

Benchmark                                 Mode     Cnt   Score   Error   Units
ClientPb.createUser                      thrpt       3   9.118 ± 5.059  ops/ms
ClientPb.existUser                       thrpt       3   9.864 ± 3.164  ops/ms
ClientPb.getUser                         thrpt       3   9.397 ± 3.342  ops/ms
ClientPb.listUser                        thrpt       3   7.849 ± 4.646  ops/ms
ClientPb.createUser                       avgt       3   3.441 ± 2.542   ms/op
ClientPb.existUser                        avgt       3   3.305 ± 1.702   ms/op
ClientPb.getUser                          avgt       3   3.351 ± 1.032   ms/op
ClientPb.listUser                         avgt       3   4.126 ± 3.382   ms/op
ClientPb.createUser                     sample  279607   3.430 ± 0.006   ms/op
ClientPb.createUser:createUser·p0.00    sample           1.007           ms/op
ClientPb.createUser:createUser·p0.50    sample           3.326           ms/op
ClientPb.createUser:createUser·p0.90    sample           3.957           ms/op
ClientPb.createUser:createUser·p0.95    sample           4.358           ms/op
ClientPb.createUser:createUser·p0.99    sample           6.201           ms/op
ClientPb.createUser:createUser·p0.999   sample          21.430           ms/op
ClientPb.createUser:createUser·p0.9999  sample          29.264           ms/op
ClientPb.createUser:createUser·p1.00    sample          32.702           ms/op
ClientPb.existUser                      sample  284192   3.379 ± 0.006   ms/op
ClientPb.existUser:existUser·p0.00      sample           1.151           ms/op
ClientPb.existUser:existUser·p0.50      sample           3.256           ms/op
ClientPb.existUser:existUser·p0.90      sample           3.985           ms/op
ClientPb.existUser:existUser·p0.95      sample           4.596           ms/op
ClientPb.existUser:existUser·p0.99      sample           6.447           ms/op
ClientPb.existUser:existUser·p0.999     sample          18.770           ms/op
ClientPb.existUser:existUser·p0.9999    sample          28.417           ms/op
ClientPb.existUser:existUser·p1.00      sample          30.540           ms/op
ClientPb.getUser                        sample  270284   3.556 ± 0.006   ms/op
ClientPb.getUser:getUser·p0.00          sample           1.346           ms/op
ClientPb.getUser:getUser·p0.50          sample           3.449           ms/op
ClientPb.getUser:getUser·p0.90          sample           4.157           ms/op
ClientPb.getUser:getUser·p0.95          sample           4.678           ms/op
ClientPb.getUser:getUser·p0.99          sample           6.398           ms/op
ClientPb.getUser:getUser·p0.999         sample          13.021           ms/op
ClientPb.getUser:getUser·p0.9999        sample          26.278           ms/op
ClientPb.getUser:getUser·p1.00          sample          27.984           ms/op
ClientPb.listUser                       sample  234178   4.097 ± 0.007   ms/op
ClientPb.listUser:listUser·p0.00        sample           1.935           ms/op
ClientPb.listUser:listUser·p0.50        sample           3.985           ms/op
ClientPb.listUser:listUser·p0.90        sample           4.620           ms/op
ClientPb.listUser:listUser·p0.95        sample           4.940           ms/op
ClientPb.listUser:listUser·p0.99        sample           7.610           ms/op
ClientPb.listUser:listUser·p0.999       sample          17.760           ms/op
ClientPb.listUser:listUser·p0.9999      sample          28.298           ms/op
ClientPb.listUser:listUser·p1.00        sample          32.309           ms/op
