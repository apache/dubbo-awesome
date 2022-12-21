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
# Warmup Iteration   1: 1.550 ops/ms
# Warmup Iteration   2: 3.567 ops/ms
# Warmup Iteration   3: 7.428 ops/ms
Iteration   1: 7.475 ops/ms
Iteration   2: 8.017 ops/ms
Iteration   3: 7.360 ops/ms


Result "org.apache.dubbo.benchmark.ClientPb.createUser":
  7.617 ±(99.9%) 6.408 ops/ms [Average]
  (min, avg, max) = (7.360, 7.617, 8.017), stdev = 0.351
  CI (99.9%): [1.209, 14.025] (assumes normal distribution)


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

# Run progress: 8.33% complete, ETA 00:12:13
# Fork: 1 of 1
# Warmup Iteration   1: 2.232 ops/ms
# Warmup Iteration   2: 5.461 ops/ms
# Warmup Iteration   3: 7.814 ops/ms
Iteration   1: 7.776 ops/ms
Iteration   2: 8.100 ops/ms
Iteration   3: 8.334 ops/ms


Result "org.apache.dubbo.benchmark.ClientPb.existUser":
  8.070 ±(99.9%) 5.114 ops/ms [Average]
  (min, avg, max) = (7.776, 8.070, 8.334), stdev = 0.280
  CI (99.9%): [2.956, 13.185] (assumes normal distribution)


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

# Run progress: 16.67% complete, ETA 00:11:05
# Fork: 1 of 1
# Warmup Iteration   1: 2.130 ops/ms
# Warmup Iteration   2: 6.358 ops/ms
# Warmup Iteration   3: 7.451 ops/ms
Iteration   1: 7.737 ops/ms
Iteration   2: 8.203 ops/ms
Iteration   3: 8.293 ops/ms


Result "org.apache.dubbo.benchmark.ClientPb.getUser":
  8.077 ±(99.9%) 5.443 ops/ms [Average]
  (min, avg, max) = (7.737, 8.077, 8.293), stdev = 0.298
  CI (99.9%): [2.634, 13.520] (assumes normal distribution)


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

# Run progress: 25.00% complete, ETA 00:09:56
# Fork: 1 of 1
# Warmup Iteration   1: 2.352 ops/ms
# Warmup Iteration   2: 5.920 ops/ms
# Warmup Iteration   3: 6.475 ops/ms
Iteration   1: 6.701 ops/ms
Iteration   2: 6.846 ops/ms
Iteration   3: 6.489 ops/ms


Result "org.apache.dubbo.benchmark.ClientPb.listUser":
  6.679 ±(99.9%) 3.271 ops/ms [Average]
  (min, avg, max) = (6.489, 6.679, 6.846), stdev = 0.179
  CI (99.9%): [3.408, 9.949] (assumes normal distribution)


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

# Run progress: 33.33% complete, ETA 00:08:50
# Fork: 1 of 1
# Warmup Iteration   1: 14.222 ±(99.9%) 0.062 ms/op
# Warmup Iteration   2: 5.215 ±(99.9%) 0.008 ms/op
# Warmup Iteration   3: 4.388 ±(99.9%) 0.004 ms/op
Iteration   1: 4.189 ±(99.9%) 0.004 ms/op
Iteration   2: 3.996 ±(99.9%) 0.004 ms/op
Iteration   3: 3.937 ±(99.9%) 0.003 ms/op


Result "org.apache.dubbo.benchmark.ClientPb.createUser":
  4.041 ±(99.9%) 2.406 ms/op [Average]
  (min, avg, max) = (3.937, 4.041, 4.189), stdev = 0.132
  CI (99.9%): [1.634, 6.447] (assumes normal distribution)


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

# Run progress: 41.67% complete, ETA 00:07:43
# Fork: 1 of 1
# Warmup Iteration   1: 12.845 ±(99.9%) 0.053 ms/op
# Warmup Iteration   2: 4.518 ±(99.9%) 0.006 ms/op
# Warmup Iteration   3: 4.118 ±(99.9%) 0.005 ms/op
Iteration   1: 3.737 ±(99.9%) 0.010 ms/op
Iteration   2: 3.783 ±(99.9%) 0.009 ms/op
Iteration   3: 3.937 ±(99.9%) 0.005 ms/op


Result "org.apache.dubbo.benchmark.ClientPb.existUser":
  3.819 ±(99.9%) 1.904 ms/op [Average]
  (min, avg, max) = (3.737, 3.819, 3.937), stdev = 0.104
  CI (99.9%): [1.915, 5.723] (assumes normal distribution)


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

# Run progress: 50.00% complete, ETA 00:06:37
# Fork: 1 of 1
# Warmup Iteration   1: 11.890 ±(99.9%) 0.043 ms/op
# Warmup Iteration   2: 4.443 ±(99.9%) 0.006 ms/op
# Warmup Iteration   3: 4.261 ±(99.9%) 0.005 ms/op
Iteration   1: 4.237 ±(99.9%) 0.004 ms/op
Iteration   2: 3.995 ±(99.9%) 0.006 ms/op
Iteration   3: 4.063 ±(99.9%) 0.008 ms/op


Result "org.apache.dubbo.benchmark.ClientPb.getUser":
  4.098 ±(99.9%) 2.277 ms/op [Average]
  (min, avg, max) = (3.995, 4.098, 4.237), stdev = 0.125
  CI (99.9%): [1.822, 6.375] (assumes normal distribution)


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

# Run progress: 58.33% complete, ETA 00:05:31
# Fork: 1 of 1
# Warmup Iteration   1: 16.570 ±(99.9%) 0.092 ms/op
# Warmup Iteration   2: 5.594 ±(99.9%) 0.006 ms/op
# Warmup Iteration   3: 4.741 ±(99.9%) 0.009 ms/op
Iteration   1: 4.765 ±(99.9%) 0.011 ms/op
Iteration   2: 4.631 ±(99.9%) 0.011 ms/op
Iteration   3: 4.605 ±(99.9%) 0.005 ms/op


Result "org.apache.dubbo.benchmark.ClientPb.listUser":
  4.667 ±(99.9%) 1.568 ms/op [Average]
  (min, avg, max) = (4.605, 4.667, 4.765), stdev = 0.086
  CI (99.9%): [3.099, 6.235] (assumes normal distribution)


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

# Run progress: 66.67% complete, ETA 00:04:24
# Fork: 1 of 1
# Warmup Iteration   1: 14.121 ±(99.9%) 0.210 ms/op
# Warmup Iteration   2: 5.663 ±(99.9%) 0.035 ms/op
# Warmup Iteration   3: 4.579 ±(99.9%) 0.020 ms/op
Iteration   1: 4.226 ±(99.9%) 0.014 ms/op
                 createUser·p0.00:   1.307 ms/op
                 createUser·p0.50:   4.014 ms/op
                 createUser·p0.90:   4.981 ms/op
                 createUser·p0.95:   5.480 ms/op
                 createUser·p0.99:   8.159 ms/op
                 createUser·p0.999:  25.912 ms/op
                 createUser·p0.9999: 28.650 ms/op
                 createUser·p1.00:   30.867 ms/op

Iteration   2: 3.929 ±(99.9%) 0.012 ms/op
                 createUser·p0.00:   1.456 ms/op
                 createUser·p0.50:   3.748 ms/op
                 createUser·p0.90:   4.415 ms/op
                 createUser·p0.95:   5.169 ms/op
                 createUser·p0.99:   7.496 ms/op
                 createUser·p0.999:  14.909 ms/op
                 createUser·p0.9999: 28.166 ms/op
                 createUser·p1.00:   28.606 ms/op

Iteration   3: 4.137 ±(99.9%) 0.017 ms/op
                 createUser·p0.00:   1.130 ms/op
                 createUser·p0.50:   3.850 ms/op
                 createUser·p0.90:   4.923 ms/op
                 createUser·p0.95:   5.333 ms/op
                 createUser·p0.99:   7.774 ms/op
                 createUser·p0.999:  30.314 ms/op
                 createUser·p0.9999: 43.254 ms/op
                 createUser·p1.00:   43.713 ms/op



Result "org.apache.dubbo.benchmark.ClientPb.createUser":
  N = 234373
  mean =      4.094 ±(99.9%) 0.009 ms/op

  Histogram, ms/op:
    [ 0.000,  5.000) = 215882 
    [ 5.000, 10.000) = 17555 
    [10.000, 15.000) = 634 
    [15.000, 20.000) = 46 
    [20.000, 25.000) = 1 
    [25.000, 30.000) = 171 
    [30.000, 35.000) = 20 
    [35.000, 40.000) = 18 
    [40.000, 45.000) = 46 

  Percentiles, ms/op:
      p(0.0000) =      1.130 ms/op
     p(50.0000) =      3.842 ms/op
     p(90.0000) =      4.850 ms/op
     p(95.0000) =      5.358 ms/op
     p(99.0000) =      7.815 ms/op
     p(99.9000) =     25.743 ms/op
     p(99.9900) =     41.652 ms/op
     p(99.9990) =     43.667 ms/op
     p(99.9999) =     43.713 ms/op
    p(100.0000) =     43.713 ms/op


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

# Run progress: 75.00% complete, ETA 00:03:18
# Fork: 1 of 1
# Warmup Iteration   1: 12.961 ±(99.9%) 0.200 ms/op
# Warmup Iteration   2: 4.292 ±(99.9%) 0.017 ms/op
# Warmup Iteration   3: 3.896 ±(99.9%) 0.012 ms/op
Iteration   1: 3.819 ±(99.9%) 0.012 ms/op
                 existUser·p0.00:   1.614 ms/op
                 existUser·p0.50:   3.703 ms/op
                 existUser·p0.90:   4.219 ms/op
                 existUser·p0.95:   4.678 ms/op
                 existUser·p0.99:   7.397 ms/op
                 existUser·p0.999:  23.200 ms/op
                 existUser·p0.9999: 31.556 ms/op
                 existUser·p1.00:   33.456 ms/op

Iteration   2: 3.901 ±(99.9%) 0.013 ms/op
                 existUser·p0.00:   1.858 ms/op
                 existUser·p0.50:   3.715 ms/op
                 existUser·p0.90:   4.399 ms/op
                 existUser·p0.95:   5.014 ms/op
                 existUser·p0.99:   8.069 ms/op
                 existUser·p0.999:  17.271 ms/op
                 existUser·p0.9999: 27.656 ms/op
                 existUser·p1.00:   28.377 ms/op

Iteration   3: 3.714 ±(99.9%) 0.012 ms/op
                 existUser·p0.00:   1.251 ms/op
                 existUser·p0.50:   3.604 ms/op
                 existUser·p0.90:   4.067 ms/op
                 existUser·p0.95:   4.301 ms/op
                 existUser·p0.99:   6.349 ms/op
                 existUser·p0.999:  27.550 ms/op
                 existUser·p0.9999: 35.152 ms/op
                 existUser·p1.00:   36.438 ms/op



Result "org.apache.dubbo.benchmark.ClientPb.existUser":
  N = 251893
  mean =      3.810 ±(99.9%) 0.007 ms/op

  Histogram, ms/op:
    [ 0.000,  2.500) = 418 
    [ 2.500,  5.000) = 242713 
    [ 5.000,  7.500) = 6366 
    [ 7.500, 10.000) = 1576 
    [10.000, 12.500) = 412 
    [12.500, 15.000) = 71 
    [15.000, 17.500) = 76 
    [17.500, 20.000) = 5 
    [20.000, 22.500) = 2 
    [22.500, 25.000) = 51 
    [25.000, 27.500) = 70 
    [27.500, 30.000) = 48 
    [30.000, 32.500) = 40 
    [32.500, 35.000) = 36 
    [35.000, 37.500) = 9 

  Percentiles, ms/op:
      p(0.0000) =      1.251 ms/op
     p(50.0000) =      3.666 ms/op
     p(90.0000) =      4.211 ms/op
     p(95.0000) =      4.661 ms/op
     p(99.0000) =      7.397 ms/op
     p(99.9000) =     22.610 ms/op
     p(99.9900) =     33.608 ms/op
     p(99.9990) =     36.370 ms/op
     p(99.9999) =     36.438 ms/op
    p(100.0000) =     36.438 ms/op


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

# Run progress: 83.33% complete, ETA 00:02:12
# Fork: 1 of 1
# Warmup Iteration   1: 13.061 ±(99.9%) 0.184 ms/op
# Warmup Iteration   2: 4.565 ±(99.9%) 0.019 ms/op
# Warmup Iteration   3: 4.314 ±(99.9%) 0.014 ms/op
Iteration   1: 4.151 ±(99.9%) 0.017 ms/op
                 getUser·p0.00:   1.661 ms/op
                 getUser·p0.50:   3.863 ms/op
                 getUser·p0.90:   4.866 ms/op
                 getUser·p0.95:   6.103 ms/op
                 getUser·p0.99:   9.215 ms/op
                 getUser·p0.999:  26.508 ms/op
                 getUser·p0.9999: 30.147 ms/op
                 getUser·p1.00:   30.867 ms/op

Iteration   2: 3.807 ±(99.9%) 0.010 ms/op
                 getUser·p0.00:   2.228 ms/op
                 getUser·p0.50:   3.723 ms/op
                 getUser·p0.90:   4.149 ms/op
                 getUser·p0.95:   4.399 ms/op
                 getUser·p0.99:   5.652 ms/op
                 getUser·p0.999:  17.238 ms/op
                 getUser·p0.9999: 29.491 ms/op
                 getUser·p1.00:   30.048 ms/op

Iteration   3: 4.045 ±(99.9%) 0.014 ms/op
                 getUser·p0.00:   1.866 ms/op
                 getUser·p0.50:   3.883 ms/op
                 getUser·p0.90:   4.694 ms/op
                 getUser·p0.95:   5.194 ms/op
                 getUser·p0.99:   7.053 ms/op
                 getUser·p0.999:  28.541 ms/op
                 getUser·p0.9999: 33.489 ms/op
                 getUser·p1.00:   34.341 ms/op



Result "org.apache.dubbo.benchmark.ClientPb.getUser":
  N = 240039
  mean =      3.996 ±(99.9%) 0.008 ms/op

  Histogram, ms/op:
    [ 0.000,  2.500) = 77 
    [ 2.500,  5.000) = 226673 
    [ 5.000,  7.500) = 10904 
    [ 7.500, 10.000) = 1504 
    [10.000, 12.500) = 420 
    [12.500, 15.000) = 85 
    [15.000, 17.500) = 50 
    [17.500, 20.000) = 33 
    [20.000, 22.500) = 8 
    [22.500, 25.000) = 22 
    [25.000, 27.500) = 59 
    [27.500, 30.000) = 135 
    [30.000, 32.500) = 52 
    [32.500, 35.000) = 17 
    [35.000, 37.500) = 0 

  Percentiles, ms/op:
      p(0.0000) =      1.661 ms/op
     p(50.0000) =      3.797 ms/op
     p(90.0000) =      4.530 ms/op
     p(95.0000) =      5.104 ms/op
     p(99.0000) =      7.479 ms/op
     p(99.9000) =     26.313 ms/op
     p(99.9900) =     31.686 ms/op
     p(99.9990) =     34.013 ms/op
     p(99.9999) =     34.341 ms/op
    p(100.0000) =     34.341 ms/op


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

# Run progress: 91.67% complete, ETA 00:01:06
# Fork: 1 of 1
# Warmup Iteration   1: 13.571 ±(99.9%) 0.203 ms/op
# Warmup Iteration   2: 5.421 ±(99.9%) 0.027 ms/op
# Warmup Iteration   3: 5.060 ±(99.9%) 0.020 ms/op
Iteration   1: 4.705 ±(99.9%) 0.016 ms/op
                 listUser·p0.00:   1.858 ms/op
                 listUser·p0.50:   4.506 ms/op
                 listUser·p0.90:   5.145 ms/op
                 listUser·p0.95:   5.874 ms/op
                 listUser·p0.99:   8.706 ms/op
                 listUser·p0.999:  25.988 ms/op
                 listUser·p0.9999: 28.515 ms/op
                 listUser·p1.00:   29.032 ms/op

Iteration   2: 4.771 ±(99.9%) 0.014 ms/op
                 listUser·p0.00:   2.339 ms/op
                 listUser·p0.50:   4.456 ms/op
                 listUser·p0.90:   5.562 ms/op
                 listUser·p0.95:   6.275 ms/op
                 listUser·p0.99:   9.028 ms/op
                 listUser·p0.999:  19.362 ms/op
                 listUser·p0.9999: 22.521 ms/op
                 listUser·p1.00:   23.233 ms/op

Iteration   3: 4.711 ±(99.9%) 0.014 ms/op
                 listUser·p0.00:   2.716 ms/op
                 listUser·p0.50:   4.481 ms/op
                 listUser·p0.90:   5.194 ms/op
                 listUser·p0.95:   6.029 ms/op
                 listUser·p0.99:   8.716 ms/op
                 listUser·p0.999:  19.961 ms/op
                 listUser·p0.9999: 25.952 ms/op
                 listUser·p1.00:   26.083 ms/op



Result "org.apache.dubbo.benchmark.ClientPb.listUser":
  N = 202909
  mean =      4.729 ±(99.9%) 0.008 ms/op

  Histogram, ms/op:
    [ 0.000,  2.500) = 6 
    [ 2.500,  5.000) = 166870 
    [ 5.000,  7.500) = 30732 
    [ 7.500, 10.000) = 4084 
    [10.000, 12.500) = 655 
    [12.500, 15.000) = 134 
    [15.000, 17.500) = 96 
    [17.500, 20.000) = 93 
    [20.000, 22.500) = 67 
    [22.500, 25.000) = 57 
    [25.000, 27.500) = 89 

  Percentiles, ms/op:
      p(0.0000) =      1.858 ms/op
     p(50.0000) =      4.481 ms/op
     p(90.0000) =      5.333 ms/op
     p(95.0000) =      6.087 ms/op
     p(99.0000) =      8.815 ms/op
     p(99.9000) =     21.168 ms/op
     p(99.9900) =     28.034 ms/op
     p(99.9990) =     28.834 ms/op
     p(99.9999) =     29.032 ms/op
    p(100.0000) =     29.032 ms/op


# Run complete. Total time: 00:13:17

REMEMBER: The numbers below are just data. To gain reusable insights, you need to follow up on
why the numbers are the way they are. Use profilers (see -prof, -lprof), design factorial
experiments, perform baseline and negative tests that provide experimental control, make sure
the benchmarking environment is safe on JVM/OS/HW level, ask for reviews from the domain experts.
Do not assume the numbers tell you what you want them to tell.

Benchmark                                 Mode     Cnt   Score   Error   Units
ClientPb.createUser                      thrpt       3   7.617 ± 6.408  ops/ms
ClientPb.existUser                       thrpt       3   8.070 ± 5.114  ops/ms
ClientPb.getUser                         thrpt       3   8.077 ± 5.443  ops/ms
ClientPb.listUser                        thrpt       3   6.679 ± 3.271  ops/ms
ClientPb.createUser                       avgt       3   4.041 ± 2.406   ms/op
ClientPb.existUser                        avgt       3   3.819 ± 1.904   ms/op
ClientPb.getUser                          avgt       3   4.098 ± 2.277   ms/op
ClientPb.listUser                         avgt       3   4.667 ± 1.568   ms/op
ClientPb.createUser                     sample  234373   4.094 ± 0.009   ms/op
ClientPb.createUser:createUser·p0.00    sample           1.130           ms/op
ClientPb.createUser:createUser·p0.50    sample           3.842           ms/op
ClientPb.createUser:createUser·p0.90    sample           4.850           ms/op
ClientPb.createUser:createUser·p0.95    sample           5.358           ms/op
ClientPb.createUser:createUser·p0.99    sample           7.815           ms/op
ClientPb.createUser:createUser·p0.999   sample          25.743           ms/op
ClientPb.createUser:createUser·p0.9999  sample          41.652           ms/op
ClientPb.createUser:createUser·p1.00    sample          43.713           ms/op
ClientPb.existUser                      sample  251893   3.810 ± 0.007   ms/op
ClientPb.existUser:existUser·p0.00      sample           1.251           ms/op
ClientPb.existUser:existUser·p0.50      sample           3.666           ms/op
ClientPb.existUser:existUser·p0.90      sample           4.211           ms/op
ClientPb.existUser:existUser·p0.95      sample           4.661           ms/op
ClientPb.existUser:existUser·p0.99      sample           7.397           ms/op
ClientPb.existUser:existUser·p0.999     sample          22.610           ms/op
ClientPb.existUser:existUser·p0.9999    sample          33.608           ms/op
ClientPb.existUser:existUser·p1.00      sample          36.438           ms/op
ClientPb.getUser                        sample  240039   3.996 ± 0.008   ms/op
ClientPb.getUser:getUser·p0.00          sample           1.661           ms/op
ClientPb.getUser:getUser·p0.50          sample           3.797           ms/op
ClientPb.getUser:getUser·p0.90          sample           4.530           ms/op
ClientPb.getUser:getUser·p0.95          sample           5.104           ms/op
ClientPb.getUser:getUser·p0.99          sample           7.479           ms/op
ClientPb.getUser:getUser·p0.999         sample          26.313           ms/op
ClientPb.getUser:getUser·p0.9999        sample          31.686           ms/op
ClientPb.getUser:getUser·p1.00          sample          34.341           ms/op
ClientPb.listUser                       sample  202909   4.729 ± 0.008   ms/op
ClientPb.listUser:listUser·p0.00        sample           1.858           ms/op
ClientPb.listUser:listUser·p0.50        sample           4.481           ms/op
ClientPb.listUser:listUser·p0.90        sample           5.333           ms/op
ClientPb.listUser:listUser·p0.95        sample           6.087           ms/op
ClientPb.listUser:listUser·p0.99        sample           8.815           ms/op
ClientPb.listUser:listUser·p0.999       sample          21.168           ms/op
ClientPb.listUser:listUser·p0.9999      sample          28.034           ms/op
ClientPb.listUser:listUser·p1.00        sample          29.032           ms/op
