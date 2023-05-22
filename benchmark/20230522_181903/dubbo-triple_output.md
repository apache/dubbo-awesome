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
# Warmup Iteration   1: 1.835 ops/ms
# Warmup Iteration   2: 4.344 ops/ms
# Warmup Iteration   3: 7.337 ops/ms
Iteration   1: 8.337 ops/ms
Iteration   2: 8.058 ops/ms
Iteration   3: 8.109 ops/ms


Result "org.apache.dubbo.benchmark.ClientPb.createUser":
  8.168 ±(99.9%) 2.708 ops/ms [Average]
  (min, avg, max) = (8.058, 8.168, 8.337), stdev = 0.148
  CI (99.9%): [5.460, 10.876] (assumes normal distribution)


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

# Run progress: 8.33% complete, ETA 00:12:10
# Fork: 1 of 1
# Warmup Iteration   1: 2.995 ops/ms
# Warmup Iteration   2: 7.891 ops/ms
# Warmup Iteration   3: 8.368 ops/ms
Iteration   1: 8.674 ops/ms
Iteration   2: 8.571 ops/ms
Iteration   3: 8.733 ops/ms


Result "org.apache.dubbo.benchmark.ClientPb.existUser":
  8.659 ±(99.9%) 1.498 ops/ms [Average]
  (min, avg, max) = (8.571, 8.659, 8.733), stdev = 0.082
  CI (99.9%): [7.161, 10.158] (assumes normal distribution)


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

# Run progress: 16.67% complete, ETA 00:11:03
# Fork: 1 of 1
# Warmup Iteration   1: 2.768 ops/ms
# Warmup Iteration   2: 7.887 ops/ms
# Warmup Iteration   3: 8.013 ops/ms
Iteration   1: 8.030 ops/ms
Iteration   2: 8.070 ops/ms
Iteration   3: 8.417 ops/ms


Result "org.apache.dubbo.benchmark.ClientPb.getUser":
  8.172 ±(99.9%) 3.879 ops/ms [Average]
  (min, avg, max) = (8.030, 8.172, 8.417), stdev = 0.213
  CI (99.9%): [4.294, 12.051] (assumes normal distribution)


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

# Run progress: 25.00% complete, ETA 00:09:56
# Fork: 1 of 1
# Warmup Iteration   1: 2.620 ops/ms
# Warmup Iteration   2: 6.692 ops/ms
# Warmup Iteration   3: 6.962 ops/ms
Iteration   1: 7.285 ops/ms
Iteration   2: 7.591 ops/ms
Iteration   3: 7.079 ops/ms


Result "org.apache.dubbo.benchmark.ClientPb.listUser":
  7.318 ±(99.9%) 4.702 ops/ms [Average]
  (min, avg, max) = (7.079, 7.318, 7.591), stdev = 0.258
  CI (99.9%): [2.616, 12.020] (assumes normal distribution)


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

# Run progress: 33.33% complete, ETA 00:08:50
# Fork: 1 of 1
# Warmup Iteration   1: 12.648 ±(99.9%) 0.088 ms/op
# Warmup Iteration   2: 4.331 ±(99.9%) 0.007 ms/op
# Warmup Iteration   3: 3.995 ±(99.9%) 0.010 ms/op
Iteration   1: 3.717 ±(99.9%) 0.005 ms/op
Iteration   2: 3.788 ±(99.9%) 0.008 ms/op
Iteration   3: 3.996 ±(99.9%) 0.006 ms/op


Result "org.apache.dubbo.benchmark.ClientPb.createUser":
  3.834 ±(99.9%) 2.642 ms/op [Average]
  (min, avg, max) = (3.717, 3.834, 3.996), stdev = 0.145
  CI (99.9%): [1.192, 6.475] (assumes normal distribution)


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

# Run progress: 41.67% complete, ETA 00:07:42
# Fork: 1 of 1
# Warmup Iteration   1: 9.155 ±(99.9%) 0.041 ms/op
# Warmup Iteration   2: 3.968 ±(99.9%) 0.005 ms/op
# Warmup Iteration   3: 3.914 ±(99.9%) 0.005 ms/op
Iteration   1: 3.792 ±(99.9%) 0.008 ms/op
Iteration   2: 3.717 ±(99.9%) 0.004 ms/op
Iteration   3: 3.704 ±(99.9%) 0.005 ms/op


Result "org.apache.dubbo.benchmark.ClientPb.existUser":
  3.738 ±(99.9%) 0.867 ms/op [Average]
  (min, avg, max) = (3.704, 3.738, 3.792), stdev = 0.047
  CI (99.9%): [2.871, 4.605] (assumes normal distribution)


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
# Warmup Iteration   1: 11.130 ±(99.9%) 0.042 ms/op
# Warmup Iteration   2: 4.438 ±(99.9%) 0.007 ms/op
# Warmup Iteration   3: 3.989 ±(99.9%) 0.004 ms/op
Iteration   1: 3.918 ±(99.9%) 0.006 ms/op
Iteration   2: 3.910 ±(99.9%) 0.010 ms/op
Iteration   3: 4.018 ±(99.9%) 0.005 ms/op


Result "org.apache.dubbo.benchmark.ClientPb.getUser":
  3.949 ±(99.9%) 1.096 ms/op [Average]
  (min, avg, max) = (3.910, 3.949, 4.018), stdev = 0.060
  CI (99.9%): [2.853, 5.044] (assumes normal distribution)


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

# Run progress: 58.33% complete, ETA 00:05:30
# Fork: 1 of 1
# Warmup Iteration   1: 13.220 ±(99.9%) 0.045 ms/op
# Warmup Iteration   2: 5.192 ±(99.9%) 0.008 ms/op
# Warmup Iteration   3: 4.596 ±(99.9%) 0.009 ms/op
Iteration   1: 4.197 ±(99.9%) 0.011 ms/op
Iteration   2: 4.078 ±(99.9%) 0.012 ms/op
Iteration   3: 4.381 ±(99.9%) 0.007 ms/op


Result "org.apache.dubbo.benchmark.ClientPb.listUser":
  4.219 ±(99.9%) 2.790 ms/op [Average]
  (min, avg, max) = (4.078, 4.219, 4.381), stdev = 0.153
  CI (99.9%): [1.429, 7.009] (assumes normal distribution)


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

# Run progress: 66.67% complete, ETA 00:04:24
# Fork: 1 of 1
# Warmup Iteration   1: 11.705 ±(99.9%) 0.156 ms/op
# Warmup Iteration   2: 4.630 ±(99.9%) 0.022 ms/op
# Warmup Iteration   3: 4.238 ±(99.9%) 0.018 ms/op
Iteration   1: 3.765 ±(99.9%) 0.012 ms/op
                 createUser·p0.00:   0.772 ms/op
                 createUser·p0.50:   3.568 ms/op
                 createUser·p0.90:   4.710 ms/op
                 createUser·p0.95:   5.439 ms/op
                 createUser·p0.99:   7.209 ms/op
                 createUser·p0.999:  14.203 ms/op
                 createUser·p0.9999: 24.674 ms/op
                 createUser·p1.00:   25.559 ms/op

Iteration   2: 3.728 ±(99.9%) 0.013 ms/op
                 createUser·p0.00:   1.509 ms/op
                 createUser·p0.50:   3.555 ms/op
                 createUser·p0.90:   4.588 ms/op
                 createUser·p0.95:   5.259 ms/op
                 createUser·p0.99:   6.947 ms/op
                 createUser·p0.999:  23.835 ms/op
                 createUser·p0.9999: 29.753 ms/op
                 createUser·p1.00:   30.573 ms/op

Iteration   3: 3.485 ±(99.9%) 0.012 ms/op
                 createUser·p0.00:   1.157 ms/op
                 createUser·p0.50:   3.346 ms/op
                 createUser·p0.90:   4.153 ms/op
                 createUser·p0.95:   4.907 ms/op
                 createUser·p0.99:   6.832 ms/op
                 createUser·p0.999:  24.969 ms/op
                 createUser·p0.9999: 30.593 ms/op
                 createUser·p1.00:   32.965 ms/op



Result "org.apache.dubbo.benchmark.ClientPb.createUser":
  N = 262786
  mean =      3.655 ±(99.9%) 0.007 ms/op

  Histogram, ms/op:
    [ 0.000,  2.500) = 6406 
    [ 2.500,  5.000) = 240436 
    [ 5.000,  7.500) = 14079 
    [ 7.500, 10.000) = 1316 
    [10.000, 12.500) = 229 
    [12.500, 15.000) = 55 
    [15.000, 17.500) = 9 
    [17.500, 20.000) = 0 
    [20.000, 22.500) = 28 
    [22.500, 25.000) = 72 
    [25.000, 27.500) = 60 
    [27.500, 30.000) = 60 
    [30.000, 32.500) = 35 
    [32.500, 35.000) = 1 
    [35.000, 37.500) = 0 

  Percentiles, ms/op:
      p(0.0000) =      0.772 ms/op
     p(50.0000) =      3.482 ms/op
     p(90.0000) =      4.522 ms/op
     p(95.0000) =      5.210 ms/op
     p(99.0000) =      7.004 ms/op
     p(99.9000) =     15.188 ms/op
     p(99.9900) =     30.236 ms/op
     p(99.9990) =     31.169 ms/op
     p(99.9999) =     32.965 ms/op
    p(100.0000) =     32.965 ms/op


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
# Warmup Iteration   1: 8.501 ±(99.9%) 0.108 ms/op
# Warmup Iteration   2: 4.154 ±(99.9%) 0.017 ms/op
# Warmup Iteration   3: 4.061 ±(99.9%) 0.014 ms/op
Iteration   1: 3.900 ±(99.9%) 0.013 ms/op
                 existUser·p0.00:   1.343 ms/op
                 existUser·p0.50:   3.723 ms/op
                 existUser·p0.90:   4.751 ms/op
                 existUser·p0.95:   5.521 ms/op
                 existUser·p0.99:   7.617 ms/op
                 existUser·p0.999:  13.353 ms/op
                 existUser·p0.9999: 28.233 ms/op
                 existUser·p1.00:   29.131 ms/op

Iteration   2: 3.821 ±(99.9%) 0.012 ms/op
                 existUser·p0.00:   1.794 ms/op
                 existUser·p0.50:   3.666 ms/op
                 existUser·p0.90:   4.620 ms/op
                 existUser·p0.95:   5.349 ms/op
                 existUser·p0.99:   7.193 ms/op
                 existUser·p0.999:  13.594 ms/op
                 existUser·p0.9999: 25.416 ms/op
                 existUser·p1.00:   26.673 ms/op

Iteration   3: 3.453 ±(99.9%) 0.012 ms/op
                 existUser·p0.00:   0.797 ms/op
                 existUser·p0.50:   3.301 ms/op
                 existUser·p0.90:   4.063 ms/op
                 existUser·p0.95:   4.628 ms/op
                 existUser·p0.99:   6.857 ms/op
                 existUser·p0.999:  24.718 ms/op
                 existUser·p0.9999: 28.917 ms/op
                 existUser·p1.00:   30.179 ms/op



Result "org.apache.dubbo.benchmark.ClientPb.existUser":
  N = 258363
  mean =      3.714 ±(99.9%) 0.007 ms/op

  Histogram, ms/op:
    [ 0.000,  2.500) = 4027 
    [ 2.500,  5.000) = 238760 
    [ 5.000,  7.500) = 13319 
    [ 7.500, 10.000) = 1444 
    [10.000, 12.500) = 309 
    [12.500, 15.000) = 262 
    [15.000, 17.500) = 18 
    [17.500, 20.000) = 0 
    [20.000, 22.500) = 0 
    [22.500, 25.000) = 76 
    [25.000, 27.500) = 101 
    [27.500, 30.000) = 46 
    [30.000, 32.500) = 1 
    [32.500, 35.000) = 0 
    [35.000, 37.500) = 0 

  Percentiles, ms/op:
      p(0.0000) =      0.797 ms/op
     p(50.0000) =      3.564 ms/op
     p(90.0000) =      4.506 ms/op
     p(95.0000) =      5.235 ms/op
     p(99.0000) =      7.234 ms/op
     p(99.9000) =     14.772 ms/op
     p(99.9900) =     28.279 ms/op
     p(99.9990) =     29.639 ms/op
     p(99.9999) =     30.179 ms/op
    p(100.0000) =     30.179 ms/op


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
# Warmup Iteration   1: 10.733 ±(99.9%) 0.125 ms/op
# Warmup Iteration   2: 4.337 ±(99.9%) 0.020 ms/op
# Warmup Iteration   3: 3.872 ±(99.9%) 0.014 ms/op
Iteration   1: 3.744 ±(99.9%) 0.012 ms/op
                 getUser·p0.00:   1.528 ms/op
                 getUser·p0.50:   3.584 ms/op
                 getUser·p0.90:   4.465 ms/op
                 getUser·p0.95:   5.251 ms/op
                 getUser·p0.99:   7.340 ms/op
                 getUser·p0.999:  19.087 ms/op
                 getUser·p0.9999: 26.786 ms/op
                 getUser·p1.00:   27.263 ms/op

Iteration   2: 4.268 ±(99.9%) 0.015 ms/op
                 getUser·p0.00:   1.853 ms/op
                 getUser·p0.50:   3.990 ms/op
                 getUser·p0.90:   5.349 ms/op
                 getUser·p0.95:   6.218 ms/op
                 getUser·p0.99:   8.604 ms/op
                 getUser·p0.999:  15.976 ms/op
                 getUser·p0.9999: 30.425 ms/op
                 getUser·p1.00:   31.293 ms/op

Iteration   3: 4.264 ±(99.9%) 0.017 ms/op
                 getUser·p0.00:   1.862 ms/op
                 getUser·p0.50:   3.957 ms/op
                 getUser·p0.90:   5.317 ms/op
                 getUser·p0.95:   6.259 ms/op
                 getUser·p0.99:   8.667 ms/op
                 getUser·p0.999:  30.278 ms/op
                 getUser·p0.9999: 33.079 ms/op
                 getUser·p1.00:   37.356 ms/op



Result "org.apache.dubbo.benchmark.ClientPb.getUser":
  N = 235392
  mean =      4.076 ±(99.9%) 0.009 ms/op

  Histogram, ms/op:
    [ 0.000,  2.500) = 925 
    [ 2.500,  5.000) = 209034 
    [ 5.000,  7.500) = 21591 
    [ 7.500, 10.000) = 3006 
    [10.000, 12.500) = 373 
    [12.500, 15.000) = 114 
    [15.000, 17.500) = 82 
    [17.500, 20.000) = 45 
    [20.000, 22.500) = 27 
    [22.500, 25.000) = 16 
    [25.000, 27.500) = 28 
    [27.500, 30.000) = 60 
    [30.000, 32.500) = 75 
    [32.500, 35.000) = 15 
    [35.000, 37.500) = 1 

  Percentiles, ms/op:
      p(0.0000) =      1.528 ms/op
     p(50.0000) =      3.838 ms/op
     p(90.0000) =      5.087 ms/op
     p(95.0000) =      5.972 ms/op
     p(99.0000) =      8.298 ms/op
     p(99.9000) =     19.497 ms/op
     p(99.9900) =     32.047 ms/op
     p(99.9990) =     34.517 ms/op
     p(99.9999) =     37.356 ms/op
    p(100.0000) =     37.356 ms/op


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
# Warmup Iteration   1: 14.859 ±(99.9%) 0.234 ms/op
# Warmup Iteration   2: 5.427 ±(99.9%) 0.029 ms/op
# Warmup Iteration   3: 5.147 ±(99.9%) 0.023 ms/op
Iteration   1: 4.588 ±(99.9%) 0.018 ms/op
                 listUser·p0.00:   1.710 ms/op
                 listUser·p0.50:   4.317 ms/op
                 listUser·p0.90:   5.358 ms/op
                 listUser·p0.95:   6.570 ms/op
                 listUser·p0.99:   9.110 ms/op
                 listUser·p0.999:  26.032 ms/op
                 listUser·p0.9999: 29.689 ms/op
                 listUser·p1.00:   31.195 ms/op

Iteration   2: 4.564 ±(99.9%) 0.016 ms/op
                 listUser·p0.00:   1.204 ms/op
                 listUser·p0.50:   4.317 ms/op
                 listUser·p0.90:   5.382 ms/op
                 listUser·p0.95:   6.365 ms/op
                 listUser·p0.99:   9.585 ms/op
                 listUser·p0.999:  20.513 ms/op
                 listUser·p0.9999: 25.327 ms/op
                 listUser·p1.00:   25.657 ms/op

Iteration   3: 4.601 ±(99.9%) 0.016 ms/op
                 listUser·p0.00:   1.036 ms/op
                 listUser·p0.50:   4.317 ms/op
                 listUser·p0.90:   5.603 ms/op
                 listUser·p0.95:   6.832 ms/op
                 listUser·p0.99:   9.404 ms/op
                 listUser·p0.999:  19.958 ms/op
                 listUser·p0.9999: 23.265 ms/op
                 listUser·p1.00:   23.921 ms/op



Result "org.apache.dubbo.benchmark.ClientPb.listUser":
  N = 209370
  mean =      4.584 ±(99.9%) 0.010 ms/op

  Histogram, ms/op:
    [ 0.000,  2.500) = 75 
    [ 2.500,  5.000) = 174789 
    [ 5.000,  7.500) = 28413 
    [ 7.500, 10.000) = 4505 
    [10.000, 12.500) = 838 
    [12.500, 15.000) = 238 
    [15.000, 17.500) = 124 
    [17.500, 20.000) = 85 
    [20.000, 22.500) = 109 
    [22.500, 25.000) = 98 
    [25.000, 27.500) = 51 
    [27.500, 30.000) = 42 
    [30.000, 32.500) = 3 
    [32.500, 35.000) = 0 
    [35.000, 37.500) = 0 

  Percentiles, ms/op:
      p(0.0000) =      1.036 ms/op
     p(50.0000) =      4.317 ms/op
     p(90.0000) =      5.439 ms/op
     p(95.0000) =      6.627 ms/op
     p(99.0000) =      9.355 ms/op
     p(99.9000) =     22.094 ms/op
     p(99.9900) =     28.482 ms/op
     p(99.9990) =     31.076 ms/op
     p(99.9999) =     31.195 ms/op
    p(100.0000) =     31.195 ms/op


# Run complete. Total time: 00:13:13

REMEMBER: The numbers below are just data. To gain reusable insights, you need to follow up on
why the numbers are the way they are. Use profilers (see -prof, -lprof), design factorial
experiments, perform baseline and negative tests that provide experimental control, make sure
the benchmarking environment is safe on JVM/OS/HW level, ask for reviews from the domain experts.
Do not assume the numbers tell you what you want them to tell.

Benchmark                                 Mode     Cnt   Score   Error   Units
ClientPb.createUser                      thrpt       3   8.168 ± 2.708  ops/ms
ClientPb.existUser                       thrpt       3   8.659 ± 1.498  ops/ms
ClientPb.getUser                         thrpt       3   8.172 ± 3.879  ops/ms
ClientPb.listUser                        thrpt       3   7.318 ± 4.702  ops/ms
ClientPb.createUser                       avgt       3   3.834 ± 2.642   ms/op
ClientPb.existUser                        avgt       3   3.738 ± 0.867   ms/op
ClientPb.getUser                          avgt       3   3.949 ± 1.096   ms/op
ClientPb.listUser                         avgt       3   4.219 ± 2.790   ms/op
ClientPb.createUser                     sample  262786   3.655 ± 0.007   ms/op
ClientPb.createUser:createUser·p0.00    sample           0.772           ms/op
ClientPb.createUser:createUser·p0.50    sample           3.482           ms/op
ClientPb.createUser:createUser·p0.90    sample           4.522           ms/op
ClientPb.createUser:createUser·p0.95    sample           5.210           ms/op
ClientPb.createUser:createUser·p0.99    sample           7.004           ms/op
ClientPb.createUser:createUser·p0.999   sample          15.188           ms/op
ClientPb.createUser:createUser·p0.9999  sample          30.236           ms/op
ClientPb.createUser:createUser·p1.00    sample          32.965           ms/op
ClientPb.existUser                      sample  258363   3.714 ± 0.007   ms/op
ClientPb.existUser:existUser·p0.00      sample           0.797           ms/op
ClientPb.existUser:existUser·p0.50      sample           3.564           ms/op
ClientPb.existUser:existUser·p0.90      sample           4.506           ms/op
ClientPb.existUser:existUser·p0.95      sample           5.235           ms/op
ClientPb.existUser:existUser·p0.99      sample           7.234           ms/op
ClientPb.existUser:existUser·p0.999     sample          14.772           ms/op
ClientPb.existUser:existUser·p0.9999    sample          28.279           ms/op
ClientPb.existUser:existUser·p1.00      sample          30.179           ms/op
ClientPb.getUser                        sample  235392   4.076 ± 0.009   ms/op
ClientPb.getUser:getUser·p0.00          sample           1.528           ms/op
ClientPb.getUser:getUser·p0.50          sample           3.838           ms/op
ClientPb.getUser:getUser·p0.90          sample           5.087           ms/op
ClientPb.getUser:getUser·p0.95          sample           5.972           ms/op
ClientPb.getUser:getUser·p0.99          sample           8.298           ms/op
ClientPb.getUser:getUser·p0.999         sample          19.497           ms/op
ClientPb.getUser:getUser·p0.9999        sample          32.047           ms/op
ClientPb.getUser:getUser·p1.00          sample          37.356           ms/op
ClientPb.listUser                       sample  209370   4.584 ± 0.010   ms/op
ClientPb.listUser:listUser·p0.00        sample           1.036           ms/op
ClientPb.listUser:listUser·p0.50        sample           4.317           ms/op
ClientPb.listUser:listUser·p0.90        sample           5.439           ms/op
ClientPb.listUser:listUser·p0.95        sample           6.627           ms/op
ClientPb.listUser:listUser·p0.99        sample           9.355           ms/op
ClientPb.listUser:listUser·p0.999       sample          22.094           ms/op
ClientPb.listUser:listUser·p0.9999      sample          28.482           ms/op
ClientPb.listUser:listUser·p1.00        sample          31.195           ms/op
